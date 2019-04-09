# BarcodeScanner

Sample QR code scanner app that works.
From ZXing proejct @ https://github.com/zxing/

## QR Codes
* Generated from https://www.qr-code-generator.com/
  * Whatever input text is prepended with `http://` by default.
  * Specify `file:///` foe instance to avoid using the `http://` default.
  * The logo in the middle can be photoshopped and replaced.

## Issues

### Unsolved
* Seems to need 'reset' after each scan.
  * Makes one think it takes a long time to scan, but really may just need a _soft reset_ by going into history and returning.
* Is it friendly with ARCore?

### Notes
* There are several sub-folders, 'android', 'android-core', 'android-integration', etc. Had to 'mesh' them together for app to work.
  * It is a huge code-base!