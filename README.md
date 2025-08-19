# 📊 Telecom X — Análisis de Evasión de Clientes (Churn)

Este repositorio contiene el desarrollo del desafío **"Churn de Clientes"** propuesto en el programa de formación de Data Science.  
El objetivo es analizar los datos de clientes de **Telecom X**, una empresa que enfrenta una alta tasa de cancelaciones, para comprender los factores asociados a la evasión (**churn**) y proponer estrategias de retención.

---

## 🚀 Objetivos del proyecto
- Importar y manipular datos de clientes de Telecom X.  
- Aplicar un proceso de **ETL (Extracción, Transformación y Carga)** para limpiar y preparar los datos.  
- Realizar un **Análisis Exploratorio de Datos (EDA)** con métricas estadísticas y visualizaciones.  
- Identificar **patrones y factores asociados al churn**.  
- Elaborar un **informe final** con conclusiones e insights.  
- (Extra) Analizar correlaciones entre variables para apoyar futuros modelos predictivos.  

---

## 📂 Contenido del repositorio
- `TelecomX_LATAM.ipynb`: Notebook principal con todo el proceso (ETL, EDA, visualizaciones, informe final).  
- `README.md`: Este archivo de documentación.  

---

## 🔧 Tecnologías utilizadas
- **Python**  
- **Pandas** — manipulación y limpieza de datos  
- **NumPy** — operaciones numéricas  
- **Matplotlib** — visualizaciones gráficas  
- **Seaborn** — visualizaciones estadísticas

---

## 📊 Flujo de trabajo
1. **Importación de datos**: carga del dataset de clientes.  
2. **Limpieza y transformación**:
   - Conversión de valores `Yes/No` a `1/0`.  
   - Renombrado de columnas a `snake_case`.  
   - Conversión de columnas numéricas a `float`.  
   - Creación de la columna `daily_charges` (facturación diaria).  
3. **Análisis exploratorio (EDA)**:
   - Estadísticas descriptivas (media, mediana, desviación, etc.).  
   - Distribución de churn (conteo y proporciones).  
   - Churn por variables categóricas (contrato, método de pago, servicios).  
   - Churn por variables numéricas (tenure, monthly_charges, total_charges, daily_charges).  
4. **Visualizaciones**: gráficos de barras, circulares, boxplots e histogramas.  
5. **Informe final**: hallazgos, conclusiones y recomendaciones estratégicas.   

---

## 📈 Principales hallazgos
- Los **clientes con contratos month-to-month** presentan la mayor tasa de churn.  
- Los **cargos mensuales altos** están asociados a una mayor evasión.  
- El **tenure bajo (0–12 meses)** es un fuerte predictor de cancelación.  
- Métodos de pago como **electronic check** correlacionan con mayor churn.  
- Los clientes con **más servicios contratados** tienden a permanecer más tiempo.  

---

## 💡 Recomendaciones estratégicas
- Diseñar **programas de retención temprana** para clientes con baja permanencia.  
- Incentivar la migración a **contratos de largo plazo**.  
- Ofrecer **planes escalonados** que reduzcan la percepción de altos costos.  
- Promover métodos de pago automáticos.  
- Potenciar servicios adicionales (soporte técnico, seguridad online) como factores de fidelización.  

---

## 🏁 Próximos pasos
- Construcción de **modelos predictivos de churn** (regresión logística, Random Forest, XGBoost).  
- Evaluar técnicas de manejo de desbalance de clases (SMOTE, ponderación de clases).  
- Implementar **dashboards interactivos** para seguimiento en tiempo real.  
- Realizar **A/B testing** con ofertas de retención.  

---

## 👨‍💻 Autor
Desarrollado por **Mauro Amnirati** como parte del programa de formación en Data Science de Alura Latam.  

---
