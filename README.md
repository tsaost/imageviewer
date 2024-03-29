# PySide6 Image Viewer

This is a small image viewer that aims to be good looking and provide basic funtionality. It is entirely made using PySide6. Feel free to use this however you would like, as long as you credit me as the original creator

![image](https://user-images.githubusercontent.com/71030751/170262545-2d710d87-8801-4272-aef2-a0b714ebe8a9.png)
![image](https://user-images.githubusercontent.com/71030751/170262661-d224ccd3-ccd0-4aea-8f8d-064cd9f5acfd.png)
![image](https://user-images.githubusercontent.com/71030751/170262918-1e61e644-5a76-43c5-b196-547e6b4eaf93.png)

# Usage

## Installation
**If you want to use the image viewer as an actually program, 
head over to the [releases page](https://github.com/MergenStudios/image_viewer/releases) and download
the installer!
**

If you want to tinker with the source code,
follow the steps below:

You need to have python 3.6+ installed.
Install the required packages with
```
pip install PySide6
pip install qt_material
```
Then you need to clone the repository with 
```
git clone https://github.com/MergenStudios/image_viewer
```
Navigate the the folder and run main.py
```
python main.py
```

If you want to build the installer,
you have to install [Install Forge](https://installforge.net/).
You will also have to install Pyinstaller with
```
pip install Pyinstaller
```
Run pyinstaller with
```
pyinstaller main.spec
```
Open the file install_forge_project.ifp inside install forge, and tinker
with the settings however you would like. 
If you want to learn how exactly all of that works I highly recommend
you check out [this](https://www.pythonguis.com/tutorials/packaging-pyqt5-pyside2-applications-windows-pyinstaller/) tutorial.

## Keyboard Shortcuts, I guess
There are some keyboard shortcuts. I'm working on making these more intuitive, but for now they're here
```
Alt + left click    Select image to move it around. Only works when there are multiple images being displayed. Letting go of alt disables the selectoin
Ctrl + C            Copy what is currently visible to the clipboard as an image
F                   Flip everything
R                   Enable rotation
```
Other than that keep in mind that you move around by holding down left click and dragging, and
that to rotate instead of zoom with the mouse wheel rotation has to be enabled by either clicking the button
or pressing R

# Credits
- I used [qt_material](https://github.com/UN-GCPDS/qt-material) to make everything look good
