# Primero configuramos el entorno con las dependencias alineadas a este proyecto.

### Creamos un ambiente virtual, para ello corremos en terminal lo siguiente (mac):
* python3 -m venv .venv
* source .venv/bin/activate
* python3 -m pip install --upgrade pip
* python3 -m pip install "setuptools<70" "wheel<0.45"
* pip install -r requirements.txt

### Creamos un directorio en donde mlflow registrará nuestros modelos:
* mkdir mlruns
