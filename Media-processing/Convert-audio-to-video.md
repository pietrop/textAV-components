# Convert audio to video

If you convert audio to video, same as you would convert video to other video formats. You get a video file without a video track, this can cause problems.

A workaround when converting audio to video is to add an image to the video file video track, see description below.

from https://www.whoishostingthis.com/compare/ffmpeg/resources/

> ### 4. Adding Poster Image to an Audio File
> You can add a poster image to your audio file easily and the output would be a video file with an image being displayed in the front and audio in the background. This is really handy when uploading MP3 files to video hosting and sharing sites.
>
> You must copy the image in the bin folder. Then execute this command:
```
ffmpeg -loop 1 -i inputimage.jpg -i inputaudio.mp3 -c:v libx264 -c:a -strict experimental -b:a 192k -shortest outputfile.mp4
```

---

[Link to trello card: Convert audio to video](https://trello.com/c/AjGPSIvf)

##### Labels

ffmpeg, Open Source, 