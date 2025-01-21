# **📊 Predicción de Pedidos de Taxis para Sweet Lift Taxi**

## **Descripción del Proyecto**  
Sweet Lift Taxi ha recopilado datos históricos sobre pedidos de taxis en los aeropuertos. Con el objetivo de atraer a más conductores durante las horas pico, este proyecto desarrolla un modelo predictivo para estimar el número de pedidos de taxis para la próxima hora. El modelo cumple con la métrica objetivo de **RMSE ≤ 48** en el conjunto de prueba.

---

## **Propósito del Proyecto**  
Predecir la cantidad de pedidos de taxis por hora para mejorar la disponibilidad de conductores durante las horas pico. Esto optimizará la planificación operativa, reducirá los tiempos de espera para los clientes y aumentará la eficiencia del servicio.

---

## **Acciones Realizadas**
1. **Carga y Exploración de Datos:**
   - Remuestreo de datos a intervalos de una hora.
   - Creación de características de calendario como año, mes, día, hora y día de la semana.

2. **Análisis Exploratorio:**
   - Identificación de tendencias, estacionalidad y patrones en los datos históricos.
   - Visualización de la serie temporal y análisis de residuos.

3. **Entrenamiento de Modelos:**
   - Comparación de modelos de **Regresión Lineal**, **Árbol de Decisión** y **Bosque Aleatorio**.
   - Ajuste de hiperparámetros para optimizar el rendimiento.

4. **Evaluación de Desempeño:**
   - Métrica clave: **RMSE en el conjunto de prueba**.
   - Selección del modelo final basado en precisión y velocidad.

---

## **Resultados**
- **Modelo Final:** Bosque Aleatorio.  
  - **RMSE en el conjunto de prueba:** 45.58 (cumple con el objetivo de RMSE ≤ 48).  
  - Capacidad para capturar patrones estacionales y fluctuaciones en la demanda.

---

## **Tecnologías Utilizadas**
![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/-Scikit%20Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/-Seaborn-4c8cbf?style=for-the-badge)

---

## **Impacto**
- **Optimización Operativa:** Planificación eficiente para satisfacer la demanda durante las horas pico.  
- **Mejora de la Experiencia del Cliente:** Reducción de tiempos de espera para los usuarios.  
- **Soporte Estratégico:** Proporciona una herramienta predictiva que puede integrarse en sistemas de gestión operativa.

---

