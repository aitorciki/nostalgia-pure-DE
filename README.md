# nostalgia-pure-DE

An [EmulationStation-DE](https://es-de.org) 2.x port of the great [nostalgia-pure](https://retropie.org.uk/forum/topic/27611/es-theme-nostalgia-pure) theme by [Muttonheads](https://www.youtube.com/c/MuttonheadsOfficial), based on the [Nostalgia video set](https://forums.launchbox-app.com/files/file/219-nostalgia-169-video-set/) by viking, dragon57 & JPGIII, and logos by [Chicuelo](https://www.chicuelo.com.ar). A picture-only variant is provided inspired by GeekOB's [nostalgia-pute-lite](https://retropie.org.uk/forum/topic/27611/es-theme-nostalgia-pure).

The original theme relies on features unique to batocera-emulationstation's theming engine, unsupported by EmulationStation-DE 1.x (notably system view videos). The new [v2.x theming engine](https://gitlab.com/leonstyhre/emulationstation-de/-/blob/master/THEMES-DEV.md) offers equivalent capabilities, and this is a port of the theme leveraging them to offer an identical experience.

## Requirements

* A [build](https://gitlab.com/leonstyhre/emulationstation-de/-/blob/master/INSTALL-DEV.md) of current EmulationStation master branch is needed as v1.x doesn't support system view videos.
* This repo doesn't include the Nostalgia videos because of storage restrictions, the [original theme](https://retropie.org.uk/forum/topic/27611/es-theme-nostalgia-pure) must be downloaded to obtain them.

## Installation

* Clone this repo to `$HOME/.emulationstation/themes` in Linux / MacOS, or `%HOMEPATH%\.emulationstation\themes` (probably `c:\users\<username>\.emulationstation\themes`) in Windows.
* Copy all MP4s from the original `nostalgia-pure`'s `_assets/backgrounds` directory into `nostalgia-pure-DE`'s `_assets/backgrounds` directory.
* Select the theme in EmulationStation-DE's UI settings. Enjoy!

## Variants

The theme provides two variants:

* The `System Videos` variant will use a full-screen video to represent each system.
* The `System Pictures` variant will use a static picture instead of a video, useful for less powerful computers or people who prefer a "quiet" experience.

## Known issues

EmulationStation-DE 2.0 is in alpha stage and under heavy development, the new theming engine is not considered stable and things might break. Notably, as of today system videos might randomly fail to start playing on app launch until a new system is selected. This and other bugs will be ironed out as 2.0 gets closer to stable.

## Video (click to watch on Youtube)

[![Watch the video](https://img.youtube.com/vi/APlsEYw5UJc/maxresdefault.jpg)](https://youtu.be/APlsEYw5UJc)