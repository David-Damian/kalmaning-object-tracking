# Filtro de Kalman para seguimiento de objetos.

El objetivo de este proyecto es realizar seguimiento de personas en un video utilizando un _filtro de Kalman_ y un modelo pre-entrenado de aprendizaje profundo (COCO model) para procesar cada cuadro del video.

Se utiliza Python y OpenCV para procesar los cuadros de video y se genera un archivo de salida con la posición de los objetos rastreados.

## Estructura de repositorio
```
├── docs/
├── notebooks/
└── src
    ├── lib.py : Funciones para reproducir video y crear video con las bounding boxes inferidas
    ├── sort.py : implementación de SORT (algoritmo que utiliza la información de detecciones de objetos en video para dar seguimiento de los mismos)
├── README.md
├── requirements.txt

```

## Implementación
Para ejecutar este proyecto, necesitarás tener instalado lo siguiente (véase `requirements.txt`):
- Python
- Paquetes: `numpy`, `matplotlib`, `filterpy==1.4.5`, `scikit-image==0.17.2`, `lap==0.4.0`, `ffmpeg-python`, `seaborn`, `Pillow`, `numpy`

## Créditos

Este proyecto está basado en el trabajo de [niconielsen32](https://github.com/niconielsen32/ObjectTracking). Se agradece a la comunidad de código abierto por compartir su conocimiento y recursos para el beneficio de todos.

# Referencias
- [Documentación de la implementación de KF en Python](https://filterpy.readthedocs.io/en/latest/kalman/KalmanFilter.html)
- [Trabajo base](https://github.com/niconielsen32/ObjectTracking)
- [Modelos de espacio de estados](https://felipegonzalez.github.io/metodos-analiticos-mcd-2023/08-modelos-1.html)

