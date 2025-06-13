# Teclado Virtual Controlado con la Mano 

Este proyecto consiste en un teclado virtual controlado por el movimiento del dedo índice, detectado en tiempo real mediante una cámara web utilizando MediaPipe y OpenCV. Pensado para usuarios con dificultades motrices que no pueden usar un teclado físico.

---

## Funcionalidades

- Interfaz gráfica tipo teclado en pantalla
- Detección de la posición del dedo índice
- Selección de teclas con temporizador (2 segundos)
- Gesto de "dedo doblado" para borrar todo el texto
- Escritura automática en cualquier programa con PyAutoGUI

---

##  Tecnologías usadas

- Python 3
- OpenCV
- MediaPipe
- PyAutoGUI
- NumPy

---

##  Cómo ejecutar el prototipo

### 1. Instala las dependencias

Abre una terminal en la carpeta del proyecto y escribe:

```bash
pip install opencv-python mediapipe pyautogui numpy
