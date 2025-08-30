# Caso 2: Agrupamiento (Entidad Financiera)

## Contexto
Proyecto de segmentación de clientes de una entidad financiera con el fin de diseñar una estrategia de atracción de **segunda tarjeta de crédito**. Se busca validar si la hipótesis de **4 clusters** es adecuada y útil para el negocio.

## Metodología
- **Exploración**: análisis univariado y bivariado, detección de outliers y correlaciones.  
- **Preparación**: imputación de nulos, escalamiento, normalización y tratamiento de variables.  
- **Transformación**: transformación de las variables numéricas mediante **MinMaxScaler()**.  
- **Modelado**: comparación de algoritmos de agrupamiento (**K-Means, DBSCAN, Jerárquico, GMM**) y evaluación con métricas de calidad de clusters mediante el índice de Silhouette.  

## Tecnologías
- Python  
- Pandas
- Scikit-learn  
- Matplotlib, Seaborn  
- Jupyter Notebook
