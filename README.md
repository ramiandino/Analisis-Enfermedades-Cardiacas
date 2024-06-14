# Analisis-Enfermedades-Cardiacas
Este proyecto tiene como objetivo analizar un conjunto de datos de enfermedades cardíacas, filtrar los registros basados en condiciones específicas y almacenar los resultados en una base de datos SQLite para su posterior análisis.

## Estructura del Proyecto
## Carga y Exploración de Datos:

•Lectura del archivo CSV que contiene los datos de pacientes con diversas características y condiciones relacionadas con enfermedades cardíacas.
•Visualización de las primeras filas del DataFrame para entender la estructura y el contenido de los datos.

## Filtrado de Datos:

Filtrado de los datos para seleccionar solo aquellos registros donde los pacientes tienen enfermedades cardíacas (Heart Disease igual a 1), niveles de colesterol mayores a 200, y presión arterial mayor a 130.
Almacenamiento de los registros filtrados en una lista llamada resultados.

## Almacenamiento en SQLite:

• Creación de una base de datos SQLite llamada heart_disease.db.
• Creación de una tabla llamada heart_disease_data para almacenar los registros filtrados.
• Inserción de los datos filtrados en la tabla de la base de datos.

## Verificación de Datos:
• Recuperación y visualización del contenido de la tabla heart_disease_data para verificar que los datos se han insertado correctamente.

## Requisitos:

**• Python 3**
**• Pandas**
**• SQLite3**
**• pyodbc (solo si usas ODBC para otras bases de datos)**

## Archivos del Proyecto
heart_disease_dataset.csv: Archivo CSV con los datos originales de los pacientes.
heart_disease_analysis.py: Script de Python que realiza todo el proceso descrito anteriormente.
