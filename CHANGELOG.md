# changelog

## Version 6.3.0
* use new @u4/opencv-build@0.6.0

## Version 6.2.5
* update @u4/opencv-build
* replace tiny-glob by @u4/tiny-glob

## Version 6.2.4
* update @u4/opencv-build

## Version 6.2.3
* update @u4/opencv-build

## Version 6.2.2
* update deps including @u4/opencv-build
* autobuild now work out of the box on common setup. (chocolatey, brew, apt)

## Version 6.2.1
* fix error message annalyse in cvLoader
* add startWindowThread()

## Version 6.2.0
* PR https://github.com/UrielCh/opencv4nodejs/pull/37
* add support for 1, 3 and 4 dimmentionals Mat
* improve debug binding usability

## Version 6.1.6
* fix issues/33 

## Version 6.1.5

* dump deps versions
* improve dry-run
* add toMatTypeName() function
* add template samples
* add cv.getScoreMax()
* add cv.dropOverlappingZone()
* add Net.dump() mapping
  
## Version 6.1.4

* Tested an works with all openCV version from 3.2.0 to 4.5.5
* small patches
* new build system, retrocompatible with origial justadudewhohacks/opencv4nodejs

## Version 6.1.3

* fix linux build regression [PR14](https://github.com/UrielCh/opencv4nodejs/pull/14)

## Version 6.1.2

* add `--node-gyp-options=<options>` param in compilation script [PR11](https://github.com/UrielCh/opencv4nodejs/pull/11)
* add doc in code
* rename _binding.gyp to binding.gyp and add a dummy "install" script
* add missing dev dependency
* improve compilation output log
* improve --dry-run mode
* bump dependencies versions

## Version 6.1.1

* fix ambiguous typing
* restructure examples
* add some bindings
* add AgeGender from [spmallick/learnopencv](https://github.com/spmallick/learnopencv/blob/master/AgeGender/)
* add ObjectDetection-YOLO from [spmallick/learnopencv](https://github.com/spmallick/learnopencv/blob/master/ObjectDetection-YOLO/)

## Version 6.1.0

* [breaking change] build-opencv action argument build is now renamed rebuild, and build, clean, configure ar now available.
* [breaking change] build-opencv -j alias of --job if gone
* testing are now converted to Typescript
* fix Typing
* fix getRegion() cordump
* add doc

## Version 6.0.12

* fix missing imports

## Version 6.0.11

* fix drawUtils.ts code
* use @u4/opencv-build 0.4.3
* add some more cv types
* start refactor cv.d.ts
* drop enum usage type WND_PROP

## Version 6.0.10

* add highgui modules
* add setWindowProperty, getWindowProperty, setWindowTitle function
* update cpp standard version to fix modern electron support

## Version 6.0.9

* enable nan module worker
* compatible with electron 9+
* add --vscode argument to generate vscode c_cpp_properties.json

## Version 6.0.8

* add support for Electron
* cleaner logs

## Version 6.0.7

* bump dependence versions inclkuding @u4/opencv-build@0.4.1
* [Fix typyings in Net.d.ts](https://github.com/UrielCh/opencv4nodejs/pull/3)
