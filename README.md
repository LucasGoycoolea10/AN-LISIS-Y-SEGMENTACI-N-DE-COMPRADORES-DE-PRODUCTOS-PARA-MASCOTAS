Proyecto de Data Science: Segmentación de Compradores de Productos para Mascotas

Integrantes del Equipo

Lucas Godoy F.

Lucas Goycoolea I.

Rodrigo Marquez N.

Introducción

Objetivo Principal:
Identificar y analizar diferentes tipos de compradores de productos para mascotas utilizando un modelo de clustering basado en un dataset de órdenes históricas. Este análisis permitirá segmentar a los consumidores según sus patrones de compra y preferencias, proporcionando insights valiosos para optimizar las estrategias comerciales.

Motivación:

Mejorar la segmentación de clientes es crucial para personalizar las estrategias de marketing y aumentar la eficiencia en la oferta de productos. Este proyecto busca proporcionar una metodología robusta y replicable para el análisis de datos de órdenes históricas en el sector de productos para mascotas.

Metodología

Selección del Dataset:

Utilizamos un dataset de Kaggle con más de un millón de filas de órdenes de compra de productos para mascotas. Este dataset incluye información detallada sobre los productos comprados, el departamento correspondiente y si el producto es una reorden.

Preparación del Dataset:

Se eliminaron los pedidos que no contenían productos del departamento de mascotas. Seleccionamos características relevantes para el clustering, como la categoría de productos y la frecuencia de reordenes. Utilizamos RStudio para realizar un análisis descriptivo inicial.

Modelos de Clustering:

Probamos varios métodos de clustering, incluyendo K-means, índice de silueta, BIC con mclust y DBSCAN. Finalmente, decidimos agrupar los departamentos manualmente utilizando la información de las distancias con respecto al departamento "pets".

Resultados

Clusters Identificados:

Cluster 1: dairy eggs, beverages, frozen, snacks.
Cluster 2: produce, pantry, household, bakery, canned goods, dry goods pasta, deli, personal care, meat, seafood, breakfast.
Cluster 3: babies, international, alcohol, missing, other, bulk.
Impacto y Aplicabilidad
Relevancia del Proyecto:
La segmentación de clientes mejora la personalización de estrategias de marketing y optimiza el inventario. Esta metodología puede aplicarse en otros mercados para guiar decisiones estratégicas y operativas.

Potencial de Implementación:

Estrategias de Marketing Personalizadas: Campañas dirigidas a cada cluster para mejorar la efectividad de las promociones.
Optimización de Inventario: Ajustar el inventario según las preferencias y patrones de compra de cada cluster.
Conclusiones
El proyecto demuestra cómo el análisis de datos y la segmentación de clientes pueden proporcionar insights valiosos que mejoran significativamente las estrategias comerciales en el mercado de productos para mascotas. La metodología de clustering aplicada ha permitido una segmentación precisa y adaptable a otros mercados, destacando el valor del análisis de clustering para decisiones estratégicas y operativas.
