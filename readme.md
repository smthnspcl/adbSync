## adbSync
[![Build Status](https://build.eberlein.io/buildStatus/icon?job=python_adbSync)](https://build.eberlein.io/job/python_adbSync/)

- sync (specific) sdcard (folders / files)
- sync (specific) installed apps
- sync wifi configuration

[![asciicast](https://asciinema.org/a/299825.svg)](https://asciinema.org/a/299825)

### how to ...

#### ... install
```
pip3 install git+https://github.com/smthnspcl/adbSync
```

#### ... use it
```
./sync.py --help
-a   | --apps
-m   | --media
-w   | --wifi               | needs su enabled for adb

e.g:
./sync.py -a -m -w
           |>>|>>\>saves wifi stuff (passwords/etc)
           |>>\>copies /sdcard/
            \>pulls all non system apps
```
