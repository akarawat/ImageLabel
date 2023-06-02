#windows install
$pip install PyQt5
$python setup.py install
------



# How to Run on window Step by Step 
from : https://1step2learn.com/en/blog/technology/install-labelimg-on-windows/
* Require python 3.10.xx
1. Dwonload zip from 
    -> https://github.com/heartexlabs/labelImg
2. Chang directory to root path 
    -> TensorFlow/addons/labelImg
3. Install dependencies
    -> C:\pip install lxml
    -> C:\pip install PyQt5
4. Uder the root directory path 
    -> Ex: C:\TensorFlow\addons>cd labelImg
5. Run pyrcc5 
    -> pyrcc5 -o libs/resources.py resources.qrc    
6. Excute labelImg.py
    -> python labelImg.py


