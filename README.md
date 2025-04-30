# Detector_Neumonia_UDD :scientist:

¡Bienvenido al proyecto final del Bootcamp de Ciencia de Datos e Inteligencia Artificial UDD! Este proyecto representa la culminación de todo lo que has aprendido a lo largo del curso. Aquí pondrás en práctica técnicas avanzadas de limpieza de datos, entrenamiento de modelos, graficación, ajuste de hiperparámetros y desarrollo de APIs.


## Objetivos  :dart:
 - Aplicar todos los conocimientos adquiridos durante el Bootcamp.
 - Consolidar técnicas de limpieza, entrenamiento, graficación y ajuste de modelos de Machine Learning.
 - Desarrollar una API que brinde predicciones basadas en datos enviados.

**Para este proyecto, seleccioné el datasets:** 

> **Imágenes de rayos X de pecho para detectar neumonía**

# Pasos del Proyecto

## Análisis Exploratorio y Limpieza de Datos: :chart_with_upwards_trend:

Realicé un análisis exploratorio de datos (EDA) para entender la estructura y características del dataset seleccionado.
Apliqué técnicas de limpieza de datos, incluyendo manejo de valores nulos.

## Entrenamiento del Modelo: :electron:
Seleccioné y entrené un modelo de Machine Learning, red neuronal adecuado para el problema planteado.
Generé predicciones de prueba para evaluar el rendimiento inicial del modelo.

## Graficación y Métricas:

Creé 2 gráficas y dos métricas de rendimiento para visualizar la precisión y rendimiento del modelo.
Realicé ajustes de hiperparámetros y ensambles para mejorar la precisión y disminuir la varianza del modelo.

## Desarrollo de la API REST: :gear:

Desarrollé una API REST que permite a los usuarios enviar datos y recibir predicciones del modelo.
La API está en el archivo api_rest.ipynb, al ejecutar este colab se hacen estos pasos:
 - Montar la ruta de google drive
 - Carga el modelo entrenado "best_mo0del.keras"
 - Configura Flask
 - Genera endpoint '/predict'
 - Ejecuta la app en Flask
 - Genera enlace de la app por eval_js

# Presentación del Proyecto: :bar_chart:

Preparé una presentación que explica el problema, el proceso de solución, las metodologías utilizadas, gráficas de rendimiento y demostraciones del modelo.
La presentación está diseñada para ser entendida por personas sin conocimientos previos en ciencia de datos e inteligencia artificial.

# Instrucciones para Ejecutar el Proyecto

1. Clonar el Repositorio:
```python
git clone https://github.com/tu-usuario/tu-repositorio.git
cd tu-repositorio
```

2.Instalar Dependencias:
```python
pip install -r requirements.txt
```

3.Ejecutar el Notebook de EDA y Entrenamiento:
```python
jupyter notebook EDA_y_Entrenamiento.ipynb
```

4.Ejecutar la API:
```python
python app.py
```

5.Acceder a la API:


La API estará disponible en link de la API (reemplaza con el link real).

# Contacto
Si tienes alguna pregunta o comentario, no dudes en contactarme a través de [mi perfil de GitHub](https://github.com/rorocabezas) o mi correo electrónico [rorocabezas@gmail.com](mailto:rorocabezas@gmail.com).
