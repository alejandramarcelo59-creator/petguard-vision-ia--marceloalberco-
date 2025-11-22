# petguard-vision-ia--marceloalberco-
PC 2 - IA GENERATIVA
PetGuard Vision IA — Análisis automático de imágenes veterinarias

Proyecto académico para análisis automático de imágenes veterinarias usando modelos de HuggingFace, como BLIP (descripción), TrOCR (OCR) y K-means (colores dominantes).

Objetivo del proyecto

Implementar un sistema capaz de analizar una imagen veterinaria y extraer:

especie inferida del animal (si es posible)

descripción automática de la imagen

texto detectado (OCR)

colores dominantes

salida exportada en formato JSON

Instrucciones de ejecución

Instalar dependencias:

pip install transformers pillow opencv-python matplotlib json5 torch torchvision

Ejecutar el script:

python src/analizar_imagen.py


resultado.json

ependencias y versiones recomendadas
Librería	Versión recomendada
Python	3.9 – 3.12
transformers	4.44+
torch	2.2+
pillow	10+
opencv-python	4.9+
numpy	1.26+
