## ubuntu:18.04

```
apt update -y && apt install -y python3 build-essential python3-pip
pip3 install esptool==2.8 pyinstaller
pyinstaller /usr/local/bin/esptool.py --onefile --clean
```