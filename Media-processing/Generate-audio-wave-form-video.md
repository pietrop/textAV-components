# Generate audio wave form video

Generate an audio wave form video from audio file.

```
ffmpeg -i test-audio.m4a -filter_complex "[0:a]showwaves=s=1920x1080:mode=line,format=yuv420p[v]" -map "[v]" -map 0:a -c:v libx264 -c:a copy output-wave.mp4
```

see video example of effect

https://youtu.be/jrY9h9OFBCM

---

[Link to trello card: Generate audio wave form video](https://trello.com/c/zkaqy4j0)

##### Labels

ffmpeg, Open Source, 