# Important Notes #

The project [Tesseract-OCR-iOS](https://github.com/gali8/Tesseract-OCR-iOS) has been forked because of an important bug that was breaking the business card feature on the Host App iOS. For more details about the bug fix, read the description of this [PR](https://github.com/SplashThat/Tesseract-OCR-iOS/pull/1).

On the source repo, a [pull request](https://github.com/gali8/Tesseract-OCR-iOS/pull/410) has been opened but it seems unlikely to be merged very soon. Therefore meanwhile, the project [BusinessCardScanner](https://github.com/SplashThat/BusinessCardScanner) is using this forked repo by installing the pod TTesseractOCRiOS.

# Tesseract OCR iOS

[![Build Status](https://travis-ci.org/gali8/Tesseract-OCR-iOS.svg?branch=master)](https://travis-ci.org/gali8/Tesseract-OCR-iOS)
[![Coverage Status](https://coveralls.io/repos/github/gali8/Tesseract-OCR-iOS/badge.svg?branch=master)](https://coveralls.io/github/gali8/Tesseract-OCR-iOS?branch=master)
[![](https://img.shields.io/cocoapods/v/TesseractOCRiOS.svg)](https://cocoapods.org/pods/Tesseractocrios)
[![](https://img.shields.io/cocoapods/p/TesseractOCRiOS.svg)](http://cocoapods.org/?q=tesseractocrios) 
[![](https://img.shields.io/cocoapods/l/TesseractOCRiOS.svg)](https://github.com/gali8/Tesseract-OCR-iOS/blob/master/LICENSE.md)

**Use Tesseract OCR in iOS 9.0+ projects written in either Objective-C or Swift.
Easy and fast.**

These are the current versions of the upstream bundled libraries within the framework that this repository provides:

* Tesseract 3.03-rc1 ([homepage](https://code.google.com/p/tesseract-ocr/))
* Leptonica 1.72 ([homepage](http://leptonica.org/))
* Image libraries (Thx to ashtons and his [libtiff-ios](https://github.com/ashtons/libtiff-ios) port):
- Libtiff 4.0.4 ([homepage](http://www.remotesensing.org/libtiff/))
- Libpng 1.6.18 ([homepage](http://www.libpng.org/pub/png/libpng.html))
- Libjpeg 9a ([homepage](http://libjpeg.sourceforge.net/))

**All libs are with bitcode integrated**


## Install

### Carthage

Add the following line to your Cartfile:
```
github "gali8/Tesseract-OCR-iOS"
```
Run `carthage update`

*Please note this is a fork, hopefully the url will change later 😸*


## Known Limitations

- macOS support using ([https://github.com/hamchapman/Tesseract-OCR-iOS/tree/macos-support](https://github.com/hamchapman/Tesseract-OCR-iOS/tree/macos-support))
- Strict requirement on language files existing in a referenced "tessdata" folder.

## Release Notes

### 3.1.1 and greater

See the [Releases](https://github.com/gali8/Tesseract-OCR-iOS/releases) page

### Older releases

See the [Release Notes wiki page](https://github.com/gali8/Tesseract-OCR-iOS/wiki/Release-Notes)



## License

Tesseract OCR iOS and TesseractOCR.framework are distributed under the MIT
license (see LICENSE.md).

Tesseract, maintained by Google (http://code.google.com/p/tesseract-ocr/), is
distributed under the Apache 2.0 license (see
http://www.apache.org/licenses/LICENSE-2.0).


Buy me a beer
=================
#### If you like my work, please buy me a beer (tap the beer):
<p align="left">
<a href="http://www.g8production.com/Beer#_=_" alt="If you like my work, please buy me a beer ">
<img style="-webkit-user-select: none;" 
src="http://68.media.tumblr.com/3243ca9030c3fa14ca3042344ae3d510/tumblr_inline_ng26w7z8SG1qmlajm.png">
</a>
</p>

## Contributors

Daniele Galiotto (founder) - Co-Founder at Nexor Technology srl -
**[www.nexor.it](http://www.nexor.it)**

Kevin Conley - **[www.kevintechnology.com](http://www.kevintechnology.com)**


Eduardo Irias - **[estamp.co](http://estamp.co)**

Hamilton Che hapman - 

