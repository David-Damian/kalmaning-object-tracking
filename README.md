# Filtro de Kalman para seguimiento de objetos.

El objetivo de este proyecto es realizar seguimiento de personas en un video utilizando un _filtro de Kalman_ y un modelo pre-entrenado de aprendizaje profundo (COCO model) para procesar cada cuadro del video.

Se utiliza Python y OpenCV para procesar los cuadros de video y se genera un archivo de salida con la posición de los objetos rastreados

## Implementación
Para ejecutar este proyecto, necesitarás tener instalado lo siguiente (véase `requirements.txt`):
- Python
- Paquetes: `numpy`, `matplotlib`, `filterpy==1.4.5`, `scikit-image==0.17.2`, `lap==0.4.0`, `ffmpeg-python`, `seaborn`, `Pillow`, `numpy`
