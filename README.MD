<center>EmotePops is a light weight browser source to display emotes on your Twitch streams!</center>

---

![Preview Image](preview.png)

## Description
EmotePops is a light weight browser source to display emotes on your Twitch streams! Emotes will appear automatically from your Twitch Chat at a random position, scale and rotation, on your Twitch Stream. Great care has been taken to ensure your emotes appear fully on the screen so you don't lose any art to the edge of the screen!

## Hosted Version
Coming Soon!

## Local Installation
I recommend you to install EmotePops locally through this message to avoid any server downtime.
1. Download this repository
2. Extract `index.html` to a destination you will remember
3. Open the file and update the `channel` const in the script section with your channel name
4. Add a browser source in OBS
    1. Tick the box next to "Local file"
    2. Click "Browse" and select `index.html`
5. Enjoy your EmotePops

## Self-Hosted Web Installation
Self-Host this overlay on your own server. This is mostly useful for streamer houses or multiple channels so you don't have to have a copy of the same file for different channels.
1. Download this repository
2. Extract `hosted.html` to a destination you will remember
3. Move it to your Webhost and change the name to `index.html`
4. Add a browser source in OBS to `https://YOURHOST.TLD/?TWITCH_USERNAME`
5. Enjoy your EmotePops

## To Do
- [ ] BetterTwitchTV Integration
- [x] Webserver Version
- [ ] Hosted Version
- [ ] Youtube Integration
- [ ] FrankerfaceZ Integration

---
<center>Created with ❤️ by [G2bb](https://twitch.tv/g2bb) - Huge thanks to @instafluff for instafluff/ComfyJS</center>
