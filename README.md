# download-youtube-video-with-command-line

This is a quick tutorial about how to download youtube video/audio with command lines. I am a mac user, so the tutoral is based on a mac environment. 

Before you starts, please install homebrew on your mac via Terminal. Check the link below to do the installation: 
https://brew.sh/ 

1. install youtub-dl,type the following commands in your terminal <br />
`brew install youtube-dl`

2. Download video to a local folder,type the following commands in your terminal 
<br /> youtube-dl -o "/local-folder-path/%(title)s.%(ext)s" "youtube-video-url"  

3. Download audio from a youtube video,type the following commands in your terminal 
> youtube-dl -o "/local-folder-path/%(title)s.%(ext)s" --extract-audio --audio-format mp3 "youtube-video-url" 
