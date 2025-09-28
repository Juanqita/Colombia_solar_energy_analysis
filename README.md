# Colombia Solar Energy Analysis 🌞💨

Este proyecto presenta un análisis exploratorio de datos climáticos (radiación solar y velocidad del viento) en tres ciudades de Colombia (**Pasto, Pereira y Valledupar**) con el fin de evaluar la viabilidad de implementar paneles solares.

## 📂 Contenido
- `analysis.ipynb` → Notebook con análisis interactivo (gráficas, resultados y explicaciones).
- `analysis.py` → Script en Python con las mismas funciones, más orientado a ejecución directa.
- `DPA.csv`, `DPE.csv`, `DVA.csv` → Archivos de datos (no incluidos en el repo por tamaño/privacidad, pero el código está preparado para cargarlos).

## ⚙️ Funcionalidades principales
- Procesamiento de datos meteorológicos (radiación solar y velocidad del viento).
- Cálculo de métricas:
  - Radiación solar promedio diaria.
  - Horas solares por día (según umbral definido).
  - Fluctuación diaria de la radiación solar.
  - Días "viables" para generación solar (según radiación máxima).
  - Correlación radiación solar ↔ viento.
- Visualizaciones:
  - Promedio diario vs umbral de viabilidad.
  - Dispersión y correlación radiación ↔ viento.
  - Comportamiento horario resaltando días viables.
  - Distribución conjunta (jointplot con `seaborn`).

## 📊 Resultados
- Se generan archivos `.csv` con los resultados para cada ciudad.
- Se identifican ciudades más aptas para instalación de paneles solares según:
  - Número de días viables.
  - Nivel de correlación positiva entre radiación solar y viento.

## 🛠️ Tecnologías usadas
- Python 3
- Pandas
- Numpy
- Matplotlib / Seaborn
- Scikit-learn
- Scipy

👤 Autor
Proyecto realizado por Juan Camilo Peláez Machado en análisis de datos, visualización y evaluación de energías renovables como parte de BootCamp.
