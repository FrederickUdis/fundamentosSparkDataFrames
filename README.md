# fundamentosSparkDataFrames
Spark SQL opera con DataFrames. Un DataFrame es una visualización relacional de la información.
Introducción a Apache Spark y DataFrames:

#  Introducción a Apache Spark y DataFrames:
Se introduce el concepto de Spark SQL y cómo opera con DataFrames.
Se menciona que un DataFrame es una representación relacional de datos, similar a una tabla en bases de datos relacionales o a DataFrames en lenguajes como Python o R.
Se destaca que Spark ofrece funciones similares a SQL y permite escribir consultas al estilo SQL.

# Configuración del Entorno:
Se instala Java en el entorno.
Se configura la variable de entorno JAVA_HOME para apuntar a la ubicación de Java.
Se descarga y extrae una versión específica de Spark.

# Instalación y Configuración de Spark:
Se instala la biblioteca findspark que facilita la inicialización de Spark en entornos como Jupyter.
Se importan las bibliotecas necesarias y se inicializa Spark.
Se crea una sesión de Spark.

# Creación de DataFrames:
Se crean dos DataFrames de ejemplo: emp y dept.
Se muestra el contenido del DataFrame emp.
Operaciones Básicas en DataFrames:

# Se presentan varias operaciones básicas que se pueden realizar en un DataFrame, como contar filas, seleccionar columnas, filtrar datos, eliminar columnas, agregar datos, ordenar datos y derivar nuevas columnas.
Joins:
Se muestra cómo realizar diferentes tipos de uniones (joins) entre DataFrames.

Consultas SQL en Spark:
Se muestra cómo ejecutar consultas al estilo SQL en Spark.
Se registra el DataFrame como una vista temporal y se ejecutan algunas consultas SQL.

Interacción con HIVE:
Se muestra cómo leer y guardar DataFrames como tablas en HIVE, tanto internas como externas.

Trabajando con Archivos CSV:
Se muestra cómo crear un DataFrame a partir de un archivo CSV y cómo guardar un DataFrame como un archivo CSV.
Interacción con Bases de Datos Relacionales:

Se muestra cómo leer y guardar DataFrames en bases de datos relacionales usando JDBC.
