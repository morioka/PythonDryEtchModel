# PythonDryEtchModel
Python tool for modeling silicon etch profile from the dry plasma etching tool in the SNF

# Demo and Features

see https://github.com/cococastano/PythonDryEtchModel

# Requirement

- WSL2 + Ubuntu20.04
- Mobaxterm (or Xserver)
- python 3.8.6

# Installation

```bash
sudo apt install libopencv-dev
pip install vtk opencv-python
pip install numpy pyvista matplotlib scipy shapely
#pip install cv2
pip install opencv-contrib-python
python -c "import cv2; print( cv2.__version__ )"


pip install open3d
pip install pyvistaqt

sudo apt install qtbase5-dev qttools5-dev-tools qt5-default
pip install pyqt5
sudo apt install libxkbcommon-x11-0
pip uninstall opencv-python opencv-contrib-python
pip install  opencv-python-headless opencv-contrib-python-headless
```

- modified the procedure of https://github.com/cococastano/PythonDryEtchModel
- To avoid QT issue, use the headless-mode opencv-python. (https://qiita.com/LemniscaterN/items/dfcda303677ca2ebf049)


# Usage

- Run Xserver and set DISPLAY environemnt variable properly in advance.

```bash
git clone https://github.com/cococastano/PythonDryEtchModel cococastano
cp -rp cococastano/ExampleMasks masks
running Xserver
python Etch_model_version12.py
```

# Note
 
TBD
 
# Author
 
This branch is modified by ymorioka@gmail.com
 
# License

TBD
