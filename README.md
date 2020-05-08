# GoProStream

**[kyhau](https://github.com/kyhau)**: My folk of [KonradIT/GoProStream](https://github.com/KonradIT/GoProStream). See [all changes here](https://github.com/kyhau/GoProStream/pulls?q=is%3Apr+is%3Aclosed).

---

Tools for handling/displaying GoPro HTTP/UDP stream. Available in Python.

## Prerequisites

- Install [Python 3](https://www.python.org/downloads/) - tested with Python 3.8.
- Download [FFmpeg](https://ffmpeg.org/download.html) (that includes `ffmpeg` and `ffplay`).
  Ensure setting `PATH` correspondingly for the script to be able to locate `ffmpeg` and `ffplay`.

## Screenshots

![](http://i.imgur.com/5wlh8yS.png) 


## Compatible with

- HERO3 
- HERO3+
- HERO4
- HERO Session
- HERO+ (incl. LCD)
- HERO5 (needs testing)

## Flags

    VERBOSE=False

Verbose flag for FFmpeg

    RECORD=False

Sends a record command to the camera, camera must be in video mode!

    SAVE=False

Save the gopro live feed to your machine

    SAVE_FILENAME="goprofeed2"

The filename of the saved video feed

    SAVE_FORMAT="mp4"

File format for saved video feed

    SAVE_LOCATION="/home/konrad/Videos/"

Location for saved video feed (needs to be changed to your username and directory)

### Further instructions

https://medium.com/@konrad_it/how-to-stream-from-a-gopro-camera-f4a164150797

### Credit

@SonOf8Bits
