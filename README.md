# California Housing Regression 🏠

Predicción del precio medio de viviendas en California utilizando modelos de regresión en Google Colab. Este proyecto compara dos modelos de regresión (Regresión Lineal y Random Forest Regressor) para determinar cuál es más efectivo en la estimación de precios, empleando el dataset de California Housing.

## Descripción 📄
Este proyecto utiliza el **California Housing Dataset**, incluido en `sklearn.datasets`. Este dataset contiene información sobre características socioeconómicas y geográficas de diferentes áreas de California, y se utiliza comúnmente para problemas de regresión.

El objetivo es predecir el precio medio de una vivienda en función de las características disponibles.

## Características del Dataset 📊
- **MedInc**: Ingreso medio de los habitantes de la zona.
- **HouseAge**: Edad promedio de las casas en la zona.
- **AveRooms**: Número promedio de habitaciones por hogar.
- **AveBedrms**: Número promedio de dormitorios por hogar.
- **Population**: Población total de la zona.
- **AveOccup**: Promedio de ocupantes por hogar.
- **Latitude**: Latitud de la zona.
- **Longitude**: Longitud de la zona.
- **MedHouseVal**: Precio medio de las viviendas (variable objetivo).

## Tecnologías 🛠️
- Python
- Scikit-learn
- NumPy
- Pandas
- Google Colab

## Estructura del Proyecto 📂
- **predictor_precio_viviendas.ipynb**: Notebook de Google Colab donde se realiza la carga de datos, preprocesamiento, entrenamiento y evaluación de los modelos.
- **requisitos.txt**: Archivo con las dependencias necesarias para ejecutar el proyecto localmente.

## Ejecución 🚀
1. Abre el archivo `predictor_precio_viviendas.ipynb` en [Google Colab](https://colab.research.google.com/).
2. Ejecuta las celdas una por una para cargar y procesar los datos, y luego entrenar los modelos.
3. Observa los resultados en las métricas de evaluación como el Mean Squared Error (MSE) y el R² Score.

## Ejemplo de Resultados 📈
| Modelo                | Mean Squared Error (MSE) | R² Score |
|-----------------------|--------------------------|----------|
| **Regresión Lineal**  | 0.50                     | 0.61     |
| **Random Forest**     | 0.23                     | 0.83     |

## Contribuciones 🤝
¡Las contribuciones son bienvenidas! Por favor, abre un *issue* o envía un *pull request* si deseas mejorar el proyecto.

## Licencia 📜
Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.
