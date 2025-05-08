# 🧠 Detector_Neumonia_UDD

¡Bienvenido al proyecto final del **Bootcamp de Ciencia de Datos e Inteligencia Artificial UDD**!  
Este repositorio representa la aplicación práctica de todos los conocimientos adquiridos durante el curso, integrando análisis de datos, entrenamiento de modelos de aprendizaje profundo y desarrollo de una API funcional.

---

## 🎯 Objetivos del Proyecto

- Aplicar técnicas avanzadas de análisis, limpieza y visualización de datos.
- Entrenar un modelo de Machine Learning (deep learning) para la detección de neumonía a partir de imágenes.
- Evaluar el rendimiento del modelo mediante métricas y visualizaciones.
- Desarrollar una **API REST** capaz de recibir imágenes de rayos X y entregar una predicción diagnóstica.

---

## 📊 Dataset Utilizado

> **Chest X-Ray Images (Pneumonia)**  
Conjunto de datos compuesto por radiografías de tórax etiquetadas para identificar la presencia o ausencia de neumonía.  
Fuente: [Inserta aquí el link del dataset si está disponible públicamente].

---

## 🔍 Flujo del Proyecto

### 1. Análisis Exploratorio y Limpieza de Datos
- Exploración inicial del conjunto de imágenes.
- Limpieza y preparación del dataset: detección de inconsistencias, balanceo de clases, normalización, etc.

### 2. Entrenamiento del Modelo
- Implementación de una red neuronal convolucional (CNN).
- Generación de predicciones iniciales y evaluación del rendimiento.
- Ajuste de hiperparámetros y uso de técnicas como ensambles o regularización.

### 3. Evaluación y Visualización
- Cálculo de métricas clave: accuracy, precision, recall, F1-score.
- Visualización mediante curvas ROC, matrices de confusión, etc.

### 4. Desarrollo de la API REST
- Creación de una API con Flask.
- Integración del modelo entrenado para recibir imágenes y retornar una predicción.
- El notebook `api_rest.ipynb` realiza los siguientes pasos:
  - Monta Google Drive.
  - Carga el modelo (`best_model.keras`).
  - Configura y lanza un servidor Flask con el endpoint `/predict`.
  - Utiliza `eval_js` para exponer la API en entorno colaborativo (Colab).

---

## 🖥️ Presentación Final

La presentación incluye:
- Introducción al problema de la neumonía infantil.
- Justificación del uso de imágenes médicas y visión por computador.
- Detalle del modelo, métricas obtenidas y resultados.
- Demostración del uso de la API.

> 🎯 *Diseñada para una audiencia general, sin conocimientos técnicos avanzados.*

---

## ⚙️ Cómo Ejecutar el Proyecto

### 1. Clona el Repositorio
```bash
git clone https://github.com/tu-usuario/tu-repositorio.git
cd tu-repositorio
```

### 2. Ejecuta el Notebook de Entrenamiento
```bash
jupyter notebook UDD_Proyecto M7_Rodrigo Cabezas.ipynb
```
### 3. Ejecuta el Notebook de API REST
```bash
jupyter notebook api_rest.ipynb
```

### 4. Accede a la API
La API estará disponible en:
Accede a la aplicación en esta url: https://5000-m-s-1erowwuj4mq80-a.asia-east1-0.prod.colab.dev  

---

## 📫 Contacto

¿Dudas o comentarios? No dudes en escribirme:

- GitHub: [@rorocabezas](https://github.com/rorocabezas)
- Correo: [rorocabezas@gmail.com](mailto:rorocabezas@gmail.com)
