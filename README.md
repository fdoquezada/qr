# QR Code Generator

Una aplicación web sencilla para generar códigos QR utilizando Flask y la librería qrcode en Python.

## Descripción

Esta aplicación permite a los usuarios generar códigos QR a partir de texto ingresado. La aplicación está construida con Flask y utiliza la librería qrcode para generar las imágenes de los códigos QR.

## Estructura del Proyecto

qr_generator/
│
├── app.py
├── requirements.txt
├── templates/
│ └── index.html
└── static/
└── styles.css


- `app.py`: Archivo principal de la aplicación Flask.
- `requirements.txt`: Lista de dependencias del proyecto.
- `templates/index.html`: Plantilla HTML para la interfaz de usuario.
- `static/styles.css`: Archivo CSS para estilos de la aplicación.

## Requisitos

- Python 3.7 o superior
- Flask
- qrcode[pil]

## Instalación

1. Clona el repositorio:

```bash
git clone https://github.com/fdoquezada/qr.git
cd qr

qr_generator/
│
├── app.py
├── requirements.txt
├── templates/
│ └── index.html
└── static/
└── styles.css


1. Clona el repositorio:


git clone https://github.com/tu_usuario/qr_generator.git
cd qr
Crea un entorno virtual y actívalo:
bash
Copiar código
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate
Instala las dependencias:
bash
Copiar código
pip install -r requirements.txt
Uso
Ejecuta la aplicación:
bash
Copiar código
python app.py
Abre tu navegador y visita http://127.0.0.1:5000/.

Ingresa el texto que deseas convertir en un código QR y haz clic en "Generate QR Code". El código QR se generará y se descargará automáticamente.

Despliegue en Render
Para desplegar esta aplicación en Render, sigue estos pasos:

Sube tu proyecto a un repositorio en GitHub.

Crea un nuevo "Web Service" en Render y conecta tu repositorio de GitHub.

Configura los siguientes parámetros en Render:

Build Command: pip install -r requirements.txt
Start Command: python app.py
Render se encargará del despliegue y proporcionará una URL donde podrás acceder a tu aplicación.

Contribuciones
Las contribuciones son bienvenidas. Por favor, abre un issue o un pull request para discutir cualquier cambio que desees realizar.

Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.