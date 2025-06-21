# Fruit-Detector-Discord-Bot
🤖 Bot Clasificador de Imágenes de frutas para Discord
Este bot de Discord usa inteligencia artificial para clasificar imágenes enviadas por los usuarios. Está desarrollado en Python y emplea un modelo de red neuronal previamente entrenado con Keras.

🔍 ¿Qué hace?
Al recibir una imagen de la fruta, el bot:
Guarda la imagen enviada por el usuario.
Preprocesa la imagen para adaptarla al modelo (tamaño, color, normalización).
Carga el modelo (keras_model.h5) y las etiquetas de clases (labels.txt).
Realiza la predicción usando el modelo.
Responde en el canal con la clase detectada y el nivel de confianza (que tan seguro cree que es la fruta).
Las frutas pueden ser: Manzanas, Plátanos, Uvas, Pitayas, Aguacates, Naranjas, Fresas
🧠 ¿Cómo funciona el modelo?
El modelo ha sido entrenado previamente con imágenes clasificadas (por ejemplo, frutas). Cada vez que recibe una nueva imagen:
La convierte en datos que el modelo entiende.
Predice la categoría más probable.
Devuelve el nombre de la clase y una puntuación de confianza (entre 0 y 100%).

📦 Tecnologías usadas:
discord.py
Keras
TensorFlow
PIL (Pillow)
NumPy

