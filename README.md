# Universidad EAFIT
# Curso ST0263 Tópicos Especiales en Telemática, 2024-2
# Retos 3,4 y 5.

- Holmer Ortega Gomez
- hortegag@eafit.edu.co

## Profesor. 
- Nombre: Edwin Nelson Montoya Munera.
- Correo: emontoya@eafit.edu.co

## Descripción General y Objetivos de los Retos y Laboratorios

Este repositorio contiene los retos y laboratorios desarrollados en el curso ST0263, enfocados en el uso de tecnologías Big Data, como Hadoop y Spark, para la gestión y procesamiento de datos en grandes volúmenes.

---

### Lab0: Introducción a la Infraestructura de Big Data

**Descripción**: El lab0 establece el entorno de trabajo en la nube utilizando Amazon EMR (Elastic MapReduce) para la configuración inicial de un clúster de Hadoop. Esto proporciona una base sólida para los laboratorios posteriores, permitiendo a los estudiantes familiarizarse con la infraestructura de Big Data y los servicios de procesamiento de datos.

**Objetivo**: Configurar y desplegar un clúster de Amazon EMR con los servicios básicos de Hadoop, HDFS, y Hue para facilitar la interacción con el sistema de archivos distribuido. Los estudiantes deben asegurarse de que el clúster esté listo para los retos posteriores, incluyendo la instalación de bibliotecas necesarias y la configuración de seguridad básica.

---

### Reto 3 (Lab3-1): Gestión de Archivos en HDFS y S3

**Descripción**: El Reto 3 introduce el manejo de archivos en Hadoop Distributed File System (HDFS) y Amazon S3. Los estudiantes deben aprender a cargar, gestionar y organizar archivos dentro del sistema de archivos distribuido y en el almacenamiento en la nube.

**Objetivo**: Familiarizarse con los comandos de HDFS y realizar tareas de gestión de archivos, como crear directorios, cargar archivos desde el sistema local hacia HDFS y copiar datos entre HDFS y S3. El reto permite a los estudiantes explorar la persistencia y volatilidad de datos en entornos distribuidos y en la nube.

---

### Reto 4 (Lab3-2): Procesamiento de Datos con Hive y SparkSQL

**Descripción**: En el Reto 4, los estudiantes utilizan Hive y SparkSQL para realizar consultas y operaciones de procesamiento en datos almacenados en HDFS y S3. Este reto está enfocado en el uso de SQL para gestionar grandes volúmenes de datos estructurados en entornos de Big Data.

**Objetivo**: Crear y manipular tablas en Hive para realizar operaciones SQL, tanto en datos estructurados almacenados en HDFS como en S3. El reto incluye la creación de tablas internas y externas, la carga de datos y el uso de SparkSQL para realizar análisis exploratorios y agregaciones. Los estudiantes también explorarán cómo almacenar y recuperar datos usando distintos formatos de almacenamiento.

---

### Reto 5 (Lab3-3): Análisis de Datos con PySpark

**Descripción**: El Reto 5 se centra en el uso de PySpark para realizar análisis de datos en grandes volúmenes. En este reto, los estudiantes trabajarán con un dataset de casos de COVID-19 en Colombia, realizando un análisis exploratorio de datos y guardando los resultados en S3 y Google Drive.

**Objetivo**: Utilizar PySpark para el procesamiento de datos en modo interactivo y mediante scripts en un entorno distribuido. Los estudiantes deben cargar un dataset en PySpark, realizar un análisis exploratorio que incluya filtrado y agregación de datos, y guardar los resultados en AWS S3 y Google Drive. Esto les permitirá comprender las capacidades de Spark para el manejo de grandes volúmenes de datos en un entorno de clúster.

---