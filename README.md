
# ScreenRecord

Description: A shell script for recording screen under linux.

Author: Donny (c) 2018

Version: 0.1.1

Dependencies: ffmpeg, notify-send (optional)

# Usage

## Help options:

-h|--help  
 &ensp; Print help options

## Record options:

-o|--output filename  
 &ensp; set the output filename

-d|--duration number  
 &ensp; record \"number\" seconds of video/gif

--delay number  
 &ensp; delay \"number\" seconds before recording

-f|--framerate number  
 &ensp; set the recording frame rate

-s|scale widthxheight  
 &ensp; scale the recording output to widthxheight

--gif  
 &ensp; output gif

--video  
 &ensp; output video; by default a video will be produced if neither --gif nor --video option is given

## Behavior options:

--noui  
 &ensp; suppress ui output, which means not using notify-send

--preview  
 &ensp; preview the parameters only, not doing actual recording

# Author

|   |
|:-:|
| [![Donny Hikari](https://avatars3.githubusercontent.com/u/22200374?s=128)](https://github.com/Donny-Hikari) |
| [Donny Hikari](https://github.com/Donny-Hikari) |
|   |
