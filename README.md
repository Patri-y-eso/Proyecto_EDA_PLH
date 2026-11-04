# 📊 Proyecto EDA: Impacto del Ocio en la Ansiedad Crónica en España (2014 vs 2025)

## 📝 Descripción del Proyecto
Este proyecto de Análisis Exploratorio de Datos (EDA) investiga la posible relación entre la oferta comercial dedicada al ocio y la hostelería, y los niveles de ansiedad crónica en la población adulta española a nivel autonómico. 

El objetivo principal es contrastar con datos demográficos, comerciales y de salud mental una hipótesis sociológica recurrente sobre el estrés urbano y la "paradoja de la elección".

### 🎯 Hipótesis Inicial
> *"Existe una correlación positiva entre la densidad de locales de ocio (hiperabundancia de opciones) y los niveles de estrés y ansiedad en las Comunidades Autónomas."*

**Veredicto tras el análisis:** ❌ Hipótesis refutada.

## 🗂️ Fuentes de Datos
Para dotar al análisis de rigor temporal y estadístico, se han cruzado microdatos y agregados del **Instituto Nacional de Estadística (INE)** en dos ventanas temporales separadas por más de una década (2014 y 2025):

*   **DIRCE (Directorio Central de Empresas):** Cuantificación de locales de ocio, cultura y hostelería (CNAEs específicos).
*   **Padrón Continuo:** Datos demográficos para la normalización de variables (cálculo per cápita / por 100k habitantes).
*   **EESE (Encuesta Europea de Salud en España):** Microdatos sobre el porcentaje de población que declara diagnóstico o síntomas de ansiedad crónica (Variable G25b_21 / C5b_22).

## 🛠️ Tecnologías y Librerías Utilizadas
*   **Python 3.8+**
*   **Pandas:** Preprocesamiento, limpieza (Data Cleaning) y agregación de datos (cruce de tipos y tratamiento de nulos).
*   **Matplotlib & Seaborn:** Visualización de datos (Análisis bivariante, Trellis plots/Facet Grids, Combo Charts).
*   **Jupyter Notebook:** Entorno de desarrollo para la memoria interactiva.

## 📂 Estructura del Repositorio
```text
├── data/
│   ├── 2014/             # Datasets históricos (DIRCE, Padrón, EESE)
│   └── 2025/             # Datasets actuales
├── notebooks/
│   └── .ipynb            # Notebooks utilizados para realizar el proyecto
├── memoria.ipynb         # Notebook principal con lo más importante de código, gráficas y explicaciones
├── presentacion.pdf      # Presentación del proyecto en pdf
├── README.md             # Presentación del proyecto

