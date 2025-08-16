# 📊 Telecom X – Predicción de Cancelación de Clientes (Churn)

## 📝 Descripción del Proyecto
Este proyecto forma parte del **Challenge Telecom X**, donde se busca predecir la **cancelación de clientes (churn)** en una empresa de telecomunicaciones.  

Tras realizar un análisis exploratorio (Parte 1), en esta segunda etapa el objetivo es **construir un pipeline de Machine Learning** que permita anticipar qué clientes tienen mayor probabilidad de cancelar sus servicios.  

El proyecto combina **preprocesamiento de datos, análisis de correlación, modelado y evaluación de clasificadores**, además de la interpretación estratégica de los resultados.

---

## 🎯 Objetivos
- Preparar los datos para el modelado (tratamiento, codificación y normalización).  
- Realizar un análisis de correlación y seleccionar variables relevantes.  
- Entrenar al menos dos modelos de clasificación.  
- Evaluar el rendimiento con métricas de clasificación.  
- Interpretar los resultados y extraer **insights estratégicos** para la empresa.  

---

## 🛠️ Tecnologías Utilizadas
- **Python**  
- **Pandas, Numpy** – manipulación y análisis de datos  
- **Matplotlib, Seaborn** – visualización de datos  
- **Scikit-learn (sklearn)** – modelado y métricas  

---

## 📂 Estructura del Proyecto
TelecomX_Churn/
│
├── data/
│ └── telecom_limpio.csv # Dataset ya limpio y preprocesado en la Parte 1
│
├── notebooks/
│ └── telecomx_churn.ipynb # Pipeline completo de ML
│
├── README.md # Documentación del proyecto


---

## 🔄 Flujo del Proyecto

1. **Carga y exploración del dataset**  
   - Se utiliza el archivo limpio generado en la Parte 1.  

2. **Preprocesamiento de datos**  
   - Eliminación de columnas irrelevantes (`ID_cliente`, `Cargos_total`).  
   - Codificación de variables categóricas.  
   - Escalado de variables numéricas.  

3. **Análisis de correlación y selección de variables**  
   - Heatmaps y revisión de multicolinealidad.  

4. **Entrenamiento de modelos**  
   - Regresión Logística.  
   - Random Forest.  
   - (Opcional: otros clasificadores como XGBoost o SVM).  

5. **Evaluación de modelos**  
   - Métricas: Accuracy, Recall, Precision, F1-score, AUC-ROC.  
   - Matriz de confusión.  

6. **Interpretación y conclusiones estratégicas**  
   - Identificación de factores más influyentes en la cancelación.  
   - Recomendaciones de negocio para reducir el churn.  

---

## 📈 Resultados Esperados
- Comparación de modelos predictivos.  
- Detección de las variables más relevantes (ej: tipo de contrato, método de pago, soporte técnico).  
- Recomendaciones para que Telecom X reduzca su tasa de cancelación.  

---

## 👩‍💻 Autor
**MariAntoJara** – Estudiante de Machine Learning  
Proyecto realizado como parte de un challenge de análisis y modelado de datos.  
