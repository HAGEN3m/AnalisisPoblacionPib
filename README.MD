# 📊 Análisis de la Relación entre Población y PIB Mundial

Este proyecto explora la relación entre la **población** y el **Producto Interno Bruto (PIB)** a lo largo del tiempo, utilizando datos económicos de países de todo el mundo. Se incluyen análisis exploratorios, modelado predictivo y visualizaciones interactivas para comunicar hallazgos clave.

---

## 🎯 Objetivo

Analizar cómo la población y el Ingreso Nacional Bruto (GNI) influyen en el crecimiento económico global. A partir de esto:

* Detectar patrones y desigualdades entre países.
* Evaluar correlaciones entre variables económicas clave.
* Predecir el PIB mediante modelos de regresión.
* Comunicar insights relevantes mediante un dashboard en Power BI.

---

## 🧠 Metodología

1. **Análisis exploratorio (EDA):** distribución de variables, outliers, correlaciones.
2. **Limpieza de datos:** filtrado, renombrado y tratamiento de nulos.
3. **Modelado predictivo:** regresión lineal múltiple para estimar el PIB.
4. **Visualizaciones finales:** creación de un dashboard interactivo.
5. **Documentación y comunicación de hallazgos.**

---

## 🛠️ Herramientas utilizadas

* Python: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`
* Jupyter Notebooks (Visual Studio Code / Anaconda)
* Power BI (dashboard final interactivo)
* Git y GitHub (control de versiones y publicación)
* Markdown para documentación clara

---

## 📁 Estructura del proyecto

```
analisisPoblacionPib/
├── data/                         # Archivos de datos originales y procesados
│   ├── Global_Economy_Indicators.csv
│   └── datos_limpios.csv
│
├── notebooks/                   # Notebooks del análisis completo
│   ├── 01_analisis_eda_preliminar.ipynb
│   ├── 02_limpieza_datos.ipynb
│   ├── 03_modelado_regresion.ipynb
│   ├── 04_visualizaciones_finales.ipynb
│   └── 05_conclusiones.ipynb
│
├── visualizaciones/            # Dashboard interactivo
│   └── dashboard_indicadores_economicos.pbix
│
├── README.md                    # Documentación principal
├── requirements.txt             # Librerías necesarias
└── .gitignore                   # Archivos/carpetas ignoradas por Git
```

---

## 🔍 Principales hallazgos

* El **PIB global** muestra un crecimiento sostenido desde 1960.
* Existe **alta correlación entre PIB, población y GNI**, especialmente en economías grandes.
* El modelo de **regresión lineal múltiple** predice el PIB con una precisión sobresaliente (R² ≈ 0.9997).
* Las economías con mayor PIB per cápita no siempre son las más pobladas.

---

## 📊 Visualización final

El proyecto incluye un **dashboard interactivo en Power BI**, con gráficos sobre:

* Evolución global del PIB por año.
* PIB acumulado por país (mapa).
* Comparación de GNI, PIB y población (gráfico de burbujas).
* PIB por país (barras apiladas por año).
* PIB per cápita acumulado por país.

📁 Ubicación: `visualizaciones/dashboard_indicadores_economicos.pbix`

---

## ✅ Cómo ejecutar el proyecto

1. Clonar el repositorio.
2. Instalar dependencias:

```bash
pip install -r requirements.txt
```

3. Abrir los notebooks desde la carpeta `notebooks/` y ejecutar paso a paso.
4. Abrir el archivo `.pbix` en Power BI Desktop para explorar el dashboard.

---

## 🚀 Próximos pasos (opcional)

* Evaluar modelos más complejos (Random Forest, XGBoost).
* Incluir más variables económicas (inflación, exportaciones, educación, etc.).
* Publicar el dashboard online para mayor accesibilidad.
