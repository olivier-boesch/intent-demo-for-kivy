# intent-demo-for-kivy

*this repo is an update of this wiki page: https://github.com/kivy/kivy/wiki/Deep-Linking-with-iOS-and-Android*
PR and comments are welcome !

A minimal demo to test intents with kivy

## Disclaimer

The IOS code wasn't already tested.

The Android code works and was tested.

## Test intent filters

### test with urls

you can open the app with two urls schemes:

* [http://myapp.org/blablabla](http://myapp.org/blablabla)
* [myapp://blablabla](myapp://blablabla)

For some mobile browsers like firefox, you'll have to 'open in an application' with a long tap on the link.

### test with barcodes (to open app with a barcode scanner)

test for http://myapp.org/this-is-a-data-intent

![link to http filter](https://github.com/olivier-boesch/intent-demo-for-kivy/raw/main/barcodes/this-is-a-data-intent.png)

test for myapp://this-is-a-data-intent

![link to app scheme](https://github.com/olivier-boesch/intent-demo-for-kivy/raw/main/barcodes/app-proto-this-is-a-data-intent.png)
