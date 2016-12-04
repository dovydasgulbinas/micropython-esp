# Running micropypthon on esp8266
Python on esp8266 ?? yes it is possible follow the steps to see how to run it

## 1. Get esp8266 binaries

1. Got to this page: [binaries](http://micropython.org/download)
2. Find in page: *Firmware for ESP8266 boards*
3. Download the latest stable build: eg. `esp8266-20161110-v1.8.6.bin`


## 2. Install python2.7 OR miniconda2

I highly recommend installing miniconda2 because its EZ to install and offers
prebuilt python packages also you will get a pip (python package manager) + virtual environment all in one!

1. Get miniconda2 from here: [miniconda2](http://conda.pydata.org/miniconda.html)
2. Open cmd/terminal & type:
```
python
<<< Python 2.7.12 |Continuum Analytics, Inc.| (default, Jun 29 2016, 11:07:13) ...
```
3. Now install esptool for uploading your binary file to esp8266
```
pip install esptool
```
4. Wipe the old firmware from your esp8266
```
python esptool.py --xxx
```

## 3. Get binaries for your esp8266

[klik-me][1]

### References
[esptool](https://github.com/espressif/esptool)
[micropython-esp8266](http://docs.micropython.org/en/latest/esp8266/)
[micropython-web-code-editor](https://github.com/micropython/webrepl)
[binaries](http://micropython.org/download)
[miniconda2](http://conda.pydata.org/miniconda.html)

[1]: www.google.com "esptool download"
