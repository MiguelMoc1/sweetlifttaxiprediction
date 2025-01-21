---

### **Predicción de Pedidos de Taxis para Sweet Lift Taxi**  
- **Descripción:**  
  Desarrollo de un modelo predictivo para estimar el número de pedidos de taxis por hora basado en datos históricos de la compañía **Sweet Lift Taxi**.  
  Este modelo ayudará a atraer más conductores durante las horas pico, mejorando la satisfacción del cliente y optimizando los recursos operativos.

- **Acciones Realizadas:**  
  - **Análisis Exploratorio:** Identificación de patrones de tendencia y estacionalidad en la serie temporal.  
  - **Remuestreo Temporal:** Conversión de datos a intervalos de una hora y generación de características como año, mes, día, hora y día de la semana.  
  - **Entrenamiento de Modelos:** Comparación de modelos como **Regresión Lineal**, **Árboles de Decisión** y **Bosques Aleatorios**.  
  - **Métrica Clave:** Cumplimiento del objetivo de RMSE ≤ 48 en el conjunto de prueba.

- **Resultados:**  
  - **Modelo Final:** Bosque Aleatorio con un RMSE de 45.58 en el conjunto de prueba.  
  - El modelo capta eficientemente los patrones estacionales y las fluctuaciones en la demanda.

- **Tecnologías Utilizadas:**  
  ![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
  ![Pandas](https://img.shields.io/badge/-Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
  ![Scikit-learn](https://img.shields.io/badge/-Scikit%20Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
  ![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
  ![Seaborn](https://img.shields.io/badge/-Seaborn-4c8cbf?style=for-the-badge)

- **Impacto:**  
  - Mejora de la planificación operativa en tiempo real para satisfacer la demanda de taxis en aeropuertos.  
  - Reducción de tiempos de espera para los clientes durante las horas pico.

---
