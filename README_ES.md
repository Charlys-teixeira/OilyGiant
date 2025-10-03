# 🛢️ OilyGiant – Selección de Pozos de Petróleo

## 📖 Descripción

Este proyecto tiene como objetivo ayudar a OilyGiant a identificar las regiones más rentables para la perforación de pozos de petróleo. El análisis incluye la previsión de volúmenes de extracción y el cálculo del riesgo financiero para respaldar decisiones estratégicas de inversión.  

## 🎯 Objetivos

- Analizar datos de tres regiones de prospección.  
- Crear modelos de regresión para predecir la producción de los pozos.  
- Evaluar la rentabilidad esperada y riesgos con bootstrapping.  
- Seleccionar la región más prometedora para inversión.  

## 🛠 Tecnologías

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

## 📌 Metodología

- Preprocesamiento de datos y escalado con StandardScaler.  
- Entrenamiento de Regresión Lineal para cada región.  
- Cálculo de ganancias considerando costos fijos y límite de pozos.  
- Evaluación de riesgo y confianza usando 1.000 muestras bootstrap.  

## 📈 Resultados

La Región X presentó la mayor ganancia esperada y el menor riesgo de pérdida. Probabilidad de pérdidas inferior al 2,5% en la región elegida. El modelo permite tomar decisiones seguras para maximizar las ganancias.  

## ✨ Conclusión

El análisis indicó la región más viable para la perforación, con un buen equilibrio entre el retorno esperado y el riesgo financiero, garantizando mayor seguridad en la inversión de OilyGiant.  
