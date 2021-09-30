# Ytdlft
`ytdlft` -- simple script to download part of video from youtube

# Requirements
- [https://github.com/ytdl-org/youtube-dl] (youtube-dl) installed
- [https://github.com/FFmpeg/FFmpeg] (ffmpeg) installed
- python 3.6+

# Usage
`ytdlft https://www.youtube.com/watch?v=dQw4w9WgXcQ -f 1:22 -t 2:11 rickroll-part.mp4`

# How it works
The script invokes `youtube-dl -g $url` and gets two urls: first for video and second for audio. Then it calls `ffmpeg` with those two urls as inputs
