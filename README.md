# Beat Sheet Studio
Beat Sheet Studio and related repositories for Shoot, Video Pencil and Squares TV

## Getting started
Grab the submodules with the following:
```
git submodule init
git submodule update
```

Make changes within the other projects then make sure this repo has the latest code using 
```
git submodule update --init --recursive
```

## Sub-projects
NB: There's generally a workspace to open.
### Video Pencil _(TelestratorApp)_ [➡](VideoPencil) 
Codebase for [Video Pencil](https://squares.tv/videopencil) and [Video Pencil Camera](https://squares.tv/videopencilcamera).

Download the (non-advanced) SDK from https://ndi-develop.go-vip.net/sdk/ ( > 700MB)

Place libndi_ios.a into `telestrator/TelestratorApp/NDIWrapper/NDIWrapper/wrapper/libndi_ios.a`

#### Targets:
* _TelestratorApp_ (ios) - Video Pencil iOS App
* _DesktopApp_ (macos) - Video Pencil Camera Mac App

### Beat Sheet [➡](BeatSheet)
Contains unified codebase for [Beat Sheet](https://squares.tv/beatsheet) and [Beat Sheet Studio](https://beatsheet.studio). 

#### Targets:
* _BeatSheet_: Beat Sheet 
* _Beat Sheet Studio_: Beat Sheet Studio

### Shoot [➡](Shoot)
Codebase for [Shoot Pro Webcam](https://shootpro.app).

#### Targets:
* _Shoot_: Shoot Pro Webcam