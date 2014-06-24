PrettyEmbed.js
==============

Prettier embeds for your YouTubes - with nice options like high-res preview images, advanced customization of embed options, and optional FitVids support.

__Usage:__
```javascript
$('#test-video').prettyEmbed({
  videoID: 'Cbti19KM3wk', //youtube video id
  //optional
  useFitVids: true, //fluid width video embed
  playerControls: true, //show play, pause buttons and progress bar
  playerInfo: false, //show video title,link etc buttons
  playerUI: 'light', //select video white theme
  playerLoop: true, //start again after video finishes 
  relatedVideos: true //show related videos
});
```
