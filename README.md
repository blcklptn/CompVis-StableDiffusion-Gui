# CompVis-StableDiffusion-Gui
Simple GUI for https://github.com/CompVis/stable-diffusion using pyqt5

## Install:
```sh
# Install requirements:
pip install pyqt5

# Move files
mv neuro-gui.py stable-diffusion/gui.py
```

## Create .exe:
```sh
# Create Executable file for windows:
cd stable-diffusion
pip install pyinstaller
pyinstaller --onefile gui.py

mv dist/gui ..
```
