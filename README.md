# Proyecto_final
Proyecto final 
Proyecto: Análisis Exploratorio del Sistema Educativo Internacional
Este proyecto realiza un Análisis Exploratorio de Datos (EDA) sobre un dataset internacional que combina información académica, digitalización educativa, asistencia, abandono escolar y rendimiento académico. El objetivo es identificar patrones, diferencias entre países y métricas clave que permitan comprender el estado global de la educación.
📁 Contenido del proyecto
El proyecto incluye:
•	Limpieza y preparación de datos
•	Unión de datasets educativos
•	Tratamiento de nulos y tipos de datos
•	Detección de outliers mediante IQR
•	Análisis descriptivo de variables
•	Comparación entre países
•	Visualizaciones (boxplots, violinplots, barplots, heatmaps)
•	Dashboard profesional en Excel
•	Conclusiones del EDA
📂 Estructura del repositorio
Código
📦 Proyecto_EDA_Educacion
 ┣ 📂 data
 ┃ ┣ student-mat.csv
 ┃ ┗ world_education.csv
 ┣ 📂 notebooks
 ┃ ┗ EDA_educacion.ipynb
 ┣ 📂 dashboard
 ┃ ┗ Dashboard_Educacion.xlsx
 ┣ 📜 README.md
 ┗ 📜 requirements.txt
🛠️ Tecnologías utilizadas
•	Python 3.10
•	Pandas
•	NumPy
•	Matplotlib
•	Seaborn
•	Jupyter Notebook
•	Excel (dashboard final)
🔧 Preparación del entorno
Instala las dependencias:
bash
pip install -r requirements.txt
O manualmente:
bash
pip install pandas numpy matplotlib seaborn openpyxl xlsxwriter
📊 Descripción del dataset
El dataset final combina:
1. student-mat.csv
•	Datos de estudiantes
•	Variables académicas y personales
•	395 registros
•	33 columnas
2. world_education.csv
•	Indicadores educativos globales
•	Digitalización
•	Abandono escolar
•	Ratio profesor/alumno
•	45.000+ registros
•	26 columnas
🧹 Limpieza y preparación
Se realizaron las siguientes tareas:
•	Carga correcta del CSV con separador ;
•	Conversión de columnas numéricas
•	Eliminación de duplicados
•	Tratamiento de nulos
•	Unión de datasets
•	Normalización de tipos de datos
•	Conversión segura con pd.to_numeric(errors="coerce")
📈 Análisis Exploratorio (EDA)
🔹 Estadísticos descriptivos
•	Medias, medianas, desviaciones
•	Distribuciones por variable
•	Identificación de valores extremos
🔹 Outliers (IQR)
Se detectaron outliers en:
•	exam_score
•	dropout_rate
•	teacher_student_ratio
Los outliers se conservaron porque aportan información relevante.
🔹 Comparación entre países
Se analizaron diferencias en:
•	Rendimiento académico
•	Asistencia
•	Graduación
•	Abandono escolar
•	Acceso a internet
•	Digitalización educativa
🔹 Visualizaciones generadas
•	Boxplots por variable
•	Violinplots
•	Barras por país
•	Heatmaps
•	Líneas comparativas
📊 Dashboard en Excel
Se creó un dashboard profesional con:
⭐ KPIs principales
•	Exam Score medio
•	Attendance Rate medio
•	Graduation Rate medio
•	Dropout Rate medio
📊 Gráficos
•	Exam Score por país
•	Attendance Rate por país
•	Graduation Rate por país
•	Internet Access por país
•	Dropout Rate por país
•	Teacher-Student Ratio
🎨 Diseño
•	Colores neutros
•	Tarjetas KPI
•	Gráficos ordenados por zonas
🧠 Conclusiones del EDA
•	El rendimiento académico varía significativamente entre países.
•	La digitalización educativa es un factor clave en los resultados.
•	La tasa de abandono escolar es un indicador crítico.
•	La relación profesor/alumno influye en el rendimiento.
•	Los países con mayor acceso digital muestran mejores métricas educativas.
📌 Limitaciones
•	Algunos datasets contienen nulos estructurales.
•	La unión de datasets requiere limpieza previa para evitar mezclas de tipos.

