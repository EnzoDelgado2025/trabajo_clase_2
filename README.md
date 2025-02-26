# trabajo_clase_2
Pregunta 1 ¿Qué es, que aplicaciones tiene y como implemento en postgres Bases de Datos Vectoriales?

Las bases de datos vectoriales son capaces de almacenar y consultar datos en forma de vectores de alta dimensión, lo cual es ideal para tareas como la búsqueda por similitud, el procesamiento del lenguaje natural y el análisis de imágenes.

En PostgreSQL, la manera más eficiente de gestionar estos datos es utilizando la extensión PGVector. Esta extensión facilita la indexación y búsqueda de embeddings utilizando métricas como la distancia coseno y la euclidiana. Su implementación incluye:

1. Activar la extensión vector para permitir columnas de vectores.

2. Definir una estructura de datos apropiada, donde cada vector representa características numéricas de una entidad.

3. Realizar consultas eficientes mediante operadores de similitud como <=>.


Pregunta 2 ¿Qué es y que aplicaciones tienen los Datalakes?

Un Data Lake es una solución de almacenamiento diseñada para manejar grandes volúmenes de datos en diversos formatos (estructurados, semiestructurados y no estructurados) sin necesidad de transformarlos previamente.

Para implementar un Data Lake, se deben considerar los siguientes aspectos:

1. Seleccionar un almacenamiento adecuado, como Amazon S3, Azure Data Lake o HDFS.

2. Definir un mecanismo de ingesta de datos, ya sea mediante pipelines ETL (Airflow, Glue) o streaming en tiempo real (Kafka, Kinesis).

3. Habilitar el procesamiento y análisis de datos con herramientas como Apache Spark, Trino o Presto.

4. Implementar controles de seguridad y gobernanza para asegurar la integridad de datos.
