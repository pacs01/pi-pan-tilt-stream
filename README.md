# Pi Pan-Tilt Stream

This is a combination of the following projects
* https://github.com/pimoroni/pantilt-hat
* https://github.com/EbenKouao/pi-camera-stream-flask

## Screenshots
TODO

## Preconditions

* Raspberry Pi 4, 2GB is recommended for optimal performance.
* Raspberry Pi 4 Camera Module or Pi HQ Camera Module (Newer version)
* Pimoroni [Pan-Tilt HAT](https://shop.pimoroni.com/products/pan-tilt-hat?variant=22408353287)
* Python 3 recommended
* virtualenv recommended

## Library dependencies
Install the following dependencies:

```
sudo apt-get update 
sudo apt-get upgrade

sudo apt-get install libatlas-base-dev
sudo apt-get install libjasper-dev
sudo apt-get install libqtgui4 
sudo apt-get install libqt4-test
sudo apt-get install libhdf5-dev

virtualenv -p <path/to/python3> venv
source venv/bin/activate
pip install -r requirements.txt
```

## Launch Web Stream

```
sudo python3 main.py
```
