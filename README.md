# Ciencia-de-Datos
<h1>Autor:</h1>
Steven Alipio Berrio - 1036661504

<h1>TITULO :Introducción al Análisis de Rendimiento Estudiantil</h1>

Este proyecto se centra en el análisis exploratorio de datos (EDA) del dataset de Rendimiento Estudiantil, que contiene información demográfica, social, familiar y académica de estudiantes de secundaria. El objetivo principal de este análisis es identificar los factores clave no académicos que influyen en las calificaciones finales de los estudiantes.

<h1>¿De qué Trata el DataFrame?</h1>
El dataset consta de 395 observaciones (estudiantes) y 33 variables, abarcando tres áreas principales:

Rendimiento Académico: Calificaciones de tres períodos (G1, G2, G3) y el historial de fracasos (failures).

Entorno Familiar y Social: Variables como el nivel educativo de los padres (Medu, Fedu), la calidad de las relaciones familiares (famrel), el consumo de alcohol (Dalc, Walc) y el estado romántico (romantic).

Hábitos de Estudio y Recursos: Tiempo de estudio semanal (studytime), apoyo escolar (schoolsup) y acceso a internet (internet).

<h1>Objetivo del Análisis</h1>
El objetivo de este EDA es doble:

Diagnóstico y Preparación de Datos: Realizar un proceso de limpieza y depuración aplicando técnicas como IQR y Z-Score para identificar y tratar valores atípicos (especialmente en variables críticas como absences), asegurando que el dataset esté robusto y listo para el modelado.

Descubrimiento de Patrones: Utilizar visualizaciones y estadísticos para determinar qué factores tienen la mayor correlación e impacto en la calificación final (G3). Buscamos responder preguntas clave, tales como:

¿Influye el nivel educativo de la madre (Medu) en la nota final?

¿El acceso a internet (internet) o el tiempo de estudio (studytime) genera una diferencia significativa en el rendimiento?

En resumen, buscamos transformar los datos brutos en información útil que pueda usarse para guiar intervenciones educativas y predecir el éxito o fracaso de los estudiantes.

<h1>Distribucion del Repositorio</h1>

├── Articulo <br>
├── Datos <br>
....├── student-mat.csv <br>
....├── student_performance_DEPURADO.csv <br>
├── proyecto_aula  <br>
....├── Entrega 1 ccia de datos.ipynb <br>
├── recursos <br>
└── sesiones_practicas <br>
└── README
