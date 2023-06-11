<div alinear="centro">

<h1>GUI de RVC<br><br>
  
Solo para inferencia de archivos de audio

   <br>

  

</div>

  

 

  
## GUI

![GUI](https://github.com/Tiger14n/RVC-GUI/raw/main/docs/GUI.JPG)
  <br><br>
  
## Configuración directa para usuarios de Windows
## [Paquete de Windows](https://github.com/Tiger14n/RVC-GUI/releases/tag/Windows-pkg)
  
<br><br>
## Preparando el ambiente


* Instale la versión de Python +3.8 si no la tiene:

* Ejecutar estos comandos

Windows con tarjetas Nvidia
```bash
python -m pip install -U rueda de herramientas de configuración de pip
pip install -U antorcha torchaudio --index-url https://download.pytorch.org/whl/cu118
pip install -r requisitos.txt
```
Otro
```
python -m pip install -U rueda de herramientas de configuración de pip
pip install -U antorcha torchaudio
pip install -r requisitos.txt
```
<br>

* Descargue [hubert_base.pt](https://huggingface.co/lj1995/VoiceConversionWebUI/resolve/main/hubert_base.pt/) y colóquelo en la carpeta raíz

<br>
 
* Luego use este comando para iniciar la GUI de RVC:
```bash
python rvcgui.py
```
O ejecute este archivo en Windows
```
RVC-GUI.bat
```

# Cargando modelos
use el botón de importación para importar un modelo desde un archivo zip,
* El .zip debe contener el archivo de peso ".pth".
* Se recomienda que el .zip contenga los archivos de recuperación de características ".index"

O coloque el modelo manualmente en root/models
```
modelos
├───Persona1
│ ├───xxxx.pth
│ ├───xxxx.índice
│ └───xxxx.npy
└───Persona2
     ├───xxxx.pth
     ├───...
     └───...
````
<br>


<br>

<br>
