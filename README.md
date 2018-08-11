# README

This repository, uses [`trello-to-markdown`](https://www.npmjs.com/package/trello-to-markdown) to pull data from trello board [`TextAV Audio and Video Components (ongoing)`](https://trello.com/b/58mo9Tpa/textav-audio-and-video-components-ongoing) and formats it so that it can be [synced with gitbook for easier browsing through the projects](https://pietropassarelli.gitbooks.io/textav-audio-and-video-components-ongoing/content/)

<!-- 
To change the content edit the trello board. -->

`Trello --> Github --> Gitbook `

## Updating the gitbook

to update [the gitbook](https://pietropassarelli.gitbooks.io/textav-audio-and-video-components-ongoing/content/) with the content of the [trello board](https://trello.com/b/58mo9Tpa/textav-audio-and-video-components-ongoing) 

Use the [github repository `textAV-components`](https://github.com/pietrop/textAV-components)

```
git clone git@github.com:pietrop/textAV-components.git
```

```
cd textAV-components
```

Then run the script ([`trello-to-markdown`](https://www.npmjs.com/package/trello-to-markdown) )
```
npm start 
```

Then git add, commit, and push to update the repository

Gitbook will synch automatically. 