FFmpegOut
=========

**FFmpegOut** is an experimental plugin that directly exports video files from
Unity with using FFmpeg as a video encoder.

Currently FFmpegOut only supports Windows.

The video format is fixed as follows:

- Container: Quicktime (mov)
- Codec: ProRes 422 (normal)

Installation
------------

The binary executable file of FFmpeg (ffmpeg.exe) is not included in this
repository nor the package because it's too huge to be included. It has to be
installed manually after downloading.

Any recent versions of FFmpeg would work nicely, but I recommend using the
following static-linked executable because I'm using this for development.

https://github.com/KeatsPeeks/ffmpeg-static/blob/master/bin/win32/x64/ffmpeg.exe

Download the file above and copy it into `Assets/StreamingAssets/FFmpegOut/`.
