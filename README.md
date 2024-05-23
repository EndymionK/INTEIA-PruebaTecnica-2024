# Inteia Prueba Tecnica 2024

El objetivo de este proyecto es generar y consumir un modelo de redes neuronales convolucionales para la segmentación de imágenes de imagenes satelitales de la tierra.

## Requisitos

- Python 3.x
- Pip
- Virtualenv
- Jupyter Notebook

## Instalación

1. Clona el repositorio: `git clone https://github.com/EndymionK/INTEIA-PruebaTecnica-2024 `
2. Crea un entorno virtual: `virtualenv venv`
3. Activa el entorno virtual: `source venv/bin/activate`
4. Instala las dependencias: `pip install -r requirements.txt`

## Estrucutra del proyecto

- `scripts/`: Contiene los scripts de Python para el analisis exploratorio de datos y la creación del modelo de redes neuronales.
- `     EDA/`: Contiene un script para el analisis exploratorio de datos.
- `     Model/`: Contiene un script para la creación del modelo de redes neuronales.
- `alternativo/`: Contiene un script alternativo para consumir un modelo entrenado en roboflow y realiza la segmentación de las 10 primeras imagenes del dataset. (Enlace al modelo: https://app.roboflow.com/inteia-jrutn/corine-land-cover-segmentation)
- `     Predicciones/`: Contiene las predicciones del modelo entrenado en roboflow.
- `RGB/`: Carpeta que contiene las imagenes RGB del dataset.(No incluida en el repositorio)
- `README.md`: Instrucciones para reproducir el proyecto.
- `requirements.txt`: Archivo con las dependencias del proyecto.


## Conclusiones

