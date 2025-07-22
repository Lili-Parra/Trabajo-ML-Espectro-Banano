# Comparación de Modelos de Clasificación a partir de datos Hiperespectrales usando Aprendizaje Automático en Plantas de Banano

Este proyecto analiza datos hiperespectrales (350–2500 nm) de hojas de plantas de banano, con el objetivo de **clasificar su estado sanitario (sana, enferma o con estrés hídrico)** y, para las enfermas, explorar el diagnóstico del tipo de enfermedad (Fusarium, Ralstonia, entre otras).

Se implementaron y compararon modelos de Machine Learning:
- Random Forest  
- XGBoost  
- LightGBM  
- CatBoost (modelo con mejor desempeño)  

La métrica principal fue el **macro F1-score**, debido al desbalance entre clases. El modelo **CatBoost** alcanzó un **98.3% de accuracy** y un **macro F1-score de 0.980**.

## Autoras
- **María Liliana Parra Osorno**  
- **Marcela Ruiz Guzmán**  

_Trabajo desarrollado para el curso de Machine Learning con el profesor Alcides, Universidad Nacional de Colombia (sede Medellín)._

## Estructura del Proyecto

