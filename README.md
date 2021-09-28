# Twitter-Gif-Maker
 My application to help with encoding and converting videos to gif to use on twitter with ffmpeg.

## Installation
* Install [FFmpeg](http://ffmpeg.zeranoe.com/builds/) for Windows.
* Download and instal [video2gif](https://github.com/NabiKAZ/video2gif).
* Download and unzip the release.

## How to use
Twitter to gif maker contains two different tools: a `mp4 video optimizer with ffmpeg method` and a `mp4 file converter to gif with 3 options of quality`

Probably you'll want to optimize your video first before converting it to mp4, so open the `EnconderProject.exe` and click in the `Compress video` button to select a mp4 file.
```
Quick note: There is a bug which makes ffmpeg unable to read files that start with numbers, for example: "34232-325" so make sure to check it.
```
After optimizing your video, you can find the results in the `results` folder.
```
The compression give you two files (one is heavier than the other) so you can choose which one you'll have to use. They are named $2.mp4 and $3.mp4.
```
With the path in hands, you can just select one from the 3 quality options to convert for a gif and the result will be in the same folder as the video.
```
Quick note: You don't need to use the same optimized video to the gif convert options, can be any .mp4 you want.
```

### Credits

A huge thanks to [NabiKAZ](https://github.com/NabiKAZ) for the creation of the video2gif, which makes it possible to have this quick and easy gif convertion.

