# Thumbnailer

[![Build Status](https://travis-ci.org/filcuc/thumbnailer.svg?branch=master)](https://travis-ci.org/filcuc/thumbnailer)
[![codecov](https://codecov.io/gh/filcuc/thumbnailer/branch/master/graph/badge.svg)](https://codecov.io/gh/filcuc/thumbnailer)



Thumbnailer is an app for creating thumbnails following the 
[XDG standard version 0.8.0](https://specifications.freedesktop.org/thumbnail-spec/thumbnail-spec-0.8.0.html)

## Supported features
- Creation of normal thumbs
- Creation of large thumbs
- Saving in XDG directory
- Saving original image last modification image in thumb PNG metadata
- Threaded image creation
- Shared repositories

## Usage
```shell script
Thumbnailer.

Usage:
  thumbnailer [--verbose] [--recursive] (--normal|--large) (--output=<dir>|--xdg) <directory>
  thumbnailer (-h | --help)
  thumbnailer --version

Options:
  -h --help           Show this screen.
  --version           Show version.
  -v --verbose        Verbose output.
  -r --recursive      Recursive scan.
  -n --normal         Generate normal thumbs.
  -l --large          Generate large thumbs.
  -o --output=<dir>   Custom Output directory
  -x --xdg            XDG directory
```

## Building
```shell script
cargo build --release
```
