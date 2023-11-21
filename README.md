# Procesador de Imágenes en Python

Este proyecto es un ejemplo de aplicación de la Programación Orientada a Objetos (OOP) en Python para procesar imágenes. Utiliza dos bibliotecas: PIL (Python Imaging Library) y OpenCV (Open Source Computer Vision Library).

## Funcionalidades

El programa permite al usuario abrir y mostrar imágenes utilizando PIL o OpenCV, dependiendo de la elección del usuario. La selección de la biblioteca y la imagen a procesar se realiza a través de la línea de comandos.

## Instalación

Antes de ejecutar el programa, hay que tener instaladas las siguientes dependencias:

- Python 3.x
- PIL (Pillow)
- OpenCV

Puede instalar las bibliotecas necesarias usando pip:

```bash
pip install Pillow
pip install opencv-python

## Para ejecutar el programa, utilice el siguiente formato de comando en su terminal:
python3 lab5.py --biblioteca [PIL/OpenCV] --imagen [ruta/a/la/imagen]
