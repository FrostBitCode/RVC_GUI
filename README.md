<div align="center">

<h1>RVC GUI<br><br>
  
For audio file inference only

  <br>

  

</div>

  



  
## GUI

![GUI](https://github.com/Tiger14n/RVC-GUI/raw/main/docs/GUI1.JPG)
  
  
<br><br>
## Preparing the environment


* Install Python version +3.8 if you have not:

* Execute these commands

For Windows and Nvidia card users
```bash
python -m pip install -U pip setuptools wheel
pip install -U torch torchaudio --index-url https://download.pytorch.org/whl/cu118
pip install -r requirements.txt
```

<br>

* Downlaod [hubert_base.pt](https://huggingface.co/lj1995/VoiceConversionWebUI/resolve/main/hubert_base.pt/) and place it in the root folder

<br>
 
* Then use this command to start RVC GUI:
```bash
python rvcgui.py
```
Or run this file on windows
```
RVC-GUI.bat
```

# Loading models
use the import button to import a model from a zip file, 
* The .zip must contain the ".pth" weight file. 
* The .zip is recommended to contain the feature retrieval files ".index, .npy"

Or place the model manually in root/models
```
Models
├───Person1
│   ├───xxxx.pth
│   ├───xxxx.index
│   └───xxxx.npy
└───Person2
    ├───xxxx.pth
    ├───...
    └───...
````
<br>




