# 📊 TelecomX – Análisis de Churn

Este proyecto corresponde al **Challenge de Data Science LATAM** donde se trabaja con datos de clientes de la empresa ficticia **TelecomX**.  
El objetivo principal es **analizar la evasión de clientes (Churn)**, identificando patrones y variables relevantes para la predicción y toma de decisiones estratégicas.  

---

## 📂 Estructura del Proyecto

El análisis se organiza en cuatro etapas principales:

1. **Extracción**
   - Obtención de los datos en formato JSON desde GitHub.
   - Conversión a DataFrame de Pandas para iniciar el análisis.

2. **Transformación**
   - Aplanado de la estructura JSON.
   - Limpieza de datos: manejo de valores nulos, duplicados y estandarización de variables.
   - Conversión de columnas numéricas y creación de nuevas variables derivadas.

3. **Carga y Análisis**
   - Estadísticas descriptivas de las variables.
   - Análisis de la variable objetivo **Churn**.
   - Visualizaciones:
     - Distribución de clientes que cancelan vs. permanecen.
     - Relación de Churn con variables categóricas (género, tipo de contrato, método de pago).
     - Relación de Churn con variables numéricas (tenure, cargos totales y mensuales).

4. **Informe Final**
   - Resumen de hallazgos:
     - Los clientes con **contratos mensuales y baja permanencia** son los más propensos a cancelar.
     - El **método de pago automático** reduce la probabilidad de churn.
     - Los **cargos totales bajos** se relacionan con clientes que abandonan, debido a poca antigüedad.
   - Recomendaciones estratégicas para la empresa.
  
   ## 📈 Tecnologías utilizadas

- **Python 3**
- **Pandas** → manipulación de datos  
- **NumPy** → operaciones numéricas  
- **Matplotlib / Seaborn** → visualización  
- **Requests** → extracción de datos desde GitHub  

---

## 🚀 Cómo usar el proyecto

1. Clonar este repositorio:
   ```bash
   git clone https://github.com/sandra16ramirez/Challenge-Telecom-X
