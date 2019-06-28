# adbSync
- sync (specific) sdcard (folders / files)
- sync (specific) installed apps
- sync wifi configuration


```
python2 sync.py --help
-a   | --apps
-m   | --media
-w   | --wifi               | needs su enabled for adb

e.g:
./sync.py -a -m -w
           |>>|>>\>saves wifi stuff (passwords/etc)
           |>>\>copies /sdcard/
            \>pulls all non system apps
```