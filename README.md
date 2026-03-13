# Proyecto-7---Explorando-factores-de-comportamiento-en-NovaRetail-
NovaRetail+ es una plataforma de comercio electrónico en Latinoamérica con millones de usuarios.  Tiene como objetivo responder:  ¿Qué factores del comportamiento del cliente están más fuertemente asociados con el ingreso anual generado?  Este proyecto es un análisis correlacional (exploratorio). Correlación ≠ causalidad.

📊 Explorando Drivers de Comportamiento en NovaRetail+
🎯 Objetivo del Proyecto
El equipo de Crecimiento y Retención de NovaRetail+, una plataforma líder de e-commerce en Latinoamérica, busca entender qué factores impulsan el ingreso anual y la retención de sus 15,000 usuarios. Este análisis identifica las conexiones críticas entre el comportamiento del usuario y el éxito financiero de la plataforma.

🛠️ Herramientas Utilizadas
Python: Lenguaje principal para el procesamiento de datos.

Pandas & NumPy: Limpieza, transformación y análisis estadístico.

Matplotlib & Seaborn: Visualización avanzada (Heatmaps, Scatterplots, Regresión).

SciPy: Pruebas de hipótesis y coeficientes de correlación especializados (Punto-Biserial, V de Cramér).

📈 Hallazgos Clave
1. El Motor de Ingresos: Transaccionalidad sobre Tráfico
Se identificó una correlación de Pearson de 0.97 entre el número de compras mensuales y el ingreso anual. Sorprendentemente, el volumen de visitas tiene una correlación mucho menor (0.34), lo que sugiere que la estrategia debe enfocarse en la conversión y el cierre de ventas más que en el tráfico genérico.

2. El Desafío del Programa Premium
A pesar de ser estadísticamente significativo (p<0.05), el estatus Premium tiene una correlación de solo 0.09 con el ingreso anual. Esto indica que los beneficios actuales no están incentivando un gasto sustancialmente mayor en comparación con los usuarios estándar.

3. Independencia de Retención
El análisis de V de Cramér reveló que factores como la región geográfica (0.015) y el tipo de dispositivo (0.007) no influyen en el abandono del cliente. La fuga de usuarios es un fenómeno transversal que requiere una estrategia de fidelización uniforme.

🚀 Próximos Pasos Sugeridos
Implementación de Segmentación RFM: Clasificar a los usuarios por Recencia, Frecuencia y Valor Monetario para personalizar campañas de marketing.

Rediseño de Beneficios Premium: Incluir incentivos basados en frecuencia (como envíos gratis ilimitados) para mover la aguja del ingreso anual.

Análisis de Outliers: Investigar el perfil de los "Super Usuarios" identificados en los scatterplots.

📂 Estructura del Repositorio
S8 Student Version-Project-NovaRetail.ipynb: Notebook principal con el flujo de análisis completo.

data/: (Opcional si tienes el CSV) Dataset de 15,000 registros de usuarios.

visuals/: Imágenes exportadas de los mapas de calor y gráficos de dispersión.
