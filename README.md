# DICOMHTJ2K
DICOM HTJ2K tools

## Features

* Transcode DICOM P10 images with any transfer syntax
* Transcode multi-frame instances
* Properly setting the photometric interpretation for color images

## Transcode DICOM P10 file to DICOM P10 HTJ2K

### Setup

Pull git submodues

> git submodule update --init --recursive

Install NPM Packages

> npm install

### Running

Transcode DICOM P10 file to DICOM P10 with HTJ2K data

> node index.js test/fixtures/dicomp10/CT1_UNC foo.dcm

## TODO

* Refactor code so it is easier to read
* Publish to npm
* Add support for batch conversion of many DICOM files
* Add transcoded images to the fixtures directory
* Add some integration tests
* Test for pathological cases (e.g. structured reports, unknown transfer syntax, etc)
