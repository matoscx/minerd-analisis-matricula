# minerd-analisis-matricula
Análisis y Modelado de la Matrícula Escolar en República Dominicana (2015-2024) 
Este repositorio contiene el proyecto final de análisis de datos y aprendizaje automático enfocado en las estadísticas del Ministerio de Educación (MINERD). El objetivo principal fue estudiar la evolución de la matrícula estudiantil por nivel educativo, regional y distrito para identificar tendencias y desarrollar modelos de estimación.

El Proyecto

Utilizamos un conjunto de datos abiertos del portal oficial de la República Dominicana con más de 1,200 registros. Analizamos cómo se distribuyen los estudiantes en los niveles Inicial, Primario, Secundario y de Adultos a lo largo de casi una década, permitiendo visualizar el impacto de las políticas públicas en diferentes zonas del país.

Lo que hicimos
Ingeniería de datos: Limpiamos y estandarizamos nombres de distritos y corregimos inconsistencias temporales en los registros.

Preprocesamiento avanzado: Implementamos codificación de variables categóricas (Label Encoding) y normalización de datos numéricos para preparar el dataset para algoritmos de Machine Learning.

Análisis Exploratorio (EDA): Creamos visualizaciones para comparar el crecimiento de la matrícula entre niveles y detectar disparidades regionales significativas.

Preparación para modelos: Estructuramos los datos para facilitar tareas de regresión o series de tiempo, enfocándonos en variables críticas como el año de inicio y el ID regional.

Herramientas utilizadas

Python como lenguaje principal.

Pandas y NumPy para el procesamiento de datos.

Matplotlib y Seaborn para la generación de gráficos estadísticos.

Scikit-learn para el escalamiento y preprocesamiento de características.

Fuente de datos
Los datos provienen del repositorio de Datos Abiertos de la República Dominicana (datos.gob.do), específicamente del dataset de estudiantes matriculados por nivel según regional y distrito.
