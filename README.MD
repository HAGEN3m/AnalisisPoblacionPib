📊 Análisis de Indicadores Económicos Mundiales

Este proyecto explora y analiza indicadores económicos a nivel global, con foco en la relación entre población, ingreso nacional bruto (GNI) y producto interno bruto (PIB). El objetivo fue evaluar si estas variables pueden ayudar a predecir el PIB de un país.

🔍 Objetivo del proyecto

Realizar un análisis exploratorio de los datos para entender patrones y relaciones clave.

Limpiar y preparar los datos para modelado.

Desarrollar un modelo de regresión lineal múltiple para predecir el PIB usando población y GNI.

Evaluar el desempeño del modelo.

📈 Dataset

El dataset incluye indicadores por país y año como:

Población

Ingreso Nacional Bruto (GNI)

Producto Interno Bruto (PIB)

Se utilizaron datos a partir del año 2000.

📊 Principales hallazgos

El crecimiento poblacional es sostenido a nivel global.

GNI y PIB presentan outliers por países con economías muy grandes.

Existe alta correlación entre PIB, GNI y población.

🔧 Modelado predictivo

Se entrenó un modelo de regresión lineal con dos variables:

X: población, gni

y: pib

Resultados:

MAE ≈ 4.34 mil millones USD

RMSE ≈ 14.19 mil millones USD

R² ≈ 0.9997

✅ El modelo muestra excelente ajuste, aunque las variables están altamente correlacionadas.

🚨 Limitaciones

Alta multicolinealidad entre población y GNI puede hacer redundante el modelo.

No se consideraron otras variables económicas (como exportaciones, educación, etc.).

Se mantuvieron outliers por su relevancia macroeconómica.

🚀 Futuras mejoras

Probar modelos no lineales o con regularización.

Incluir nuevas variables.

Crear dashboards interactivos con Power BI, Tableau o Looker Studio.

📁 Estructura del proyecto

01_analisis_eda_preliminar.ipynb: análisis exploratorio.

02_limpieza_datos.ipynb: limpieza de datos.

03_modelado_regresion.ipynb: modelo predictivo.

04_visualizaciones_finales.ipynb: gráficos clave.

05_conclusiones.ipynb: resumen y hallazgos.

🙌 Autor

Proyecto desarrollado por HAGEN3M como parte de su formación en Data Science e Inteligencia Artificial.
