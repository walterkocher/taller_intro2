# Crear y activar el entorno virtual (opcional pero recomendado)
## Crear un entorno virtual:
python -m venv venv

## Activar el entorno:
### Windows
venv\Scripts\activate
### linux/mac
source venv/bin/activate

## Instalar las dependencias

### Verifica que tienes pip actualizado:
python -m pip install --upgrade pip

### Instala las dependencias del proyecto (si hay un archivo requirements.txt):
pip install -r requirements.txt

## Configurar las credenciales de la API de Spotify

### Crea un archivo .env en la raíz del repositorio.

### Agrega las siguientes líneas, reemplazando con tus credenciales:

client_id = tu_cliente_id
client_secret = tu_cliente_secret

## Luego ejecuta cada bloque en orden del archivo "prueba.ipynb" 