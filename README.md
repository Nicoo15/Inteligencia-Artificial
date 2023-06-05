# Neuro Style Transfer

Este proyecto implementa un algoritmo de transferencia de estilo neuronal utilizando el modelo VGG19. El objetivo es combinar una imagen base con el estilo de otra imagen para crear una nueva imagen única que combine ambos elementos.

## Requisitos

- Python 3.x
- Bibliotecas de Python: Keras, TensorFlow, Matplotlib, NumPy

## Uso

1. Clona este repositorio en tu máquina local:

2. Coloca las imágenes que deseas utilizar en el directorio `fotos/`. Asegúrate de tener una imagen base y una imagen de referencia de estilo.

3. Abre el archivo `neuro_style_transfer.py` y edita las rutas de las imágenes en las variables `base_image_path` y `style_reference_image_path` con las rutas reales de tus imágenes.

4. Ejecuta el script `neuro_style_transfer.py`:

5. El script comenzará a procesar las imágenes y generar una nueva imagen combinada. El progreso y la pérdida se imprimirán en la consola.

6. Una vez completado el proceso, la imagen resultante se guardará en el directorio como `combination_image.png`.

## Personalización

- Si deseas ajustar los parámetros del algoritmo, como el número de iteraciones o los pesos de estilo y contenido, puedes modificar los valores en el script `neuro_style_transfer.py`.

- Si quieres utilizar diferentes imágenes, asegúrate de editar las rutas de las imágenes en el script.

## Contribuciones

¡Las contribuciones son bienvenidas! Si tienes ideas para mejorar este proyecto, no dudes en enviar un pull request.

## Actualizaciones
En este caso cogi un cuadro de Andy Warhol y una foto de una persona. Intente que copiara el estilo con esa cara, por temas de memoria y velocidad hay pocas iteraciones.

Ire subiendo proximamente modelos :
MACHINE LEARNING
ANN 
RNN
REINFORCEMENT LEARNING
GAN, NLP... 

QUE TENGO REALIZADOS PERO NECESITAN UN REPASO

Además, es importante mencionar que el modelo VGG19 y el algoritmo de transferencia de estilo son recursos muy pesados en términos de cálculo y memoria. Puede ser necesario ejecutar el código en un entorno con recursos adecuados (por ejemplo, una GPU potente) para obtener resultados rápidos y evitar problemas de memoria
