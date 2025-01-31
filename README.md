# 📊 Informe de Análisis Exploratorio de Datos (EDA) sobre el Rendimiento de los Estudiantes

![](Portada_Estudiantes_EDA.png)

> 💡 También puedes visualizar este informe de análisis en el siguiente enlace de Kaggle: [Rendimiento de los Estudiantes - Análisis Exploratorio de Datos (EDA) - Anderson Rodríguez](https://www.kaggle.com/code/andersonrodriguezs/analisis-exploratorio-de-datos-en-espa-ol)

## 📝 Introducción

En este proyecto, hemos realizado un Análisis Exploratorio de Datos (EDA) sobre un conjunto de datos que contiene información relacionada con el rendimiento de los estudiantes. El objetivo principal es comprender los factores que influyen en el rendimiento académico y preparar los datos para su posterior análisis o modelado.

## 🔍 Descripción del Conjunto de Datos

El conjunto de datos consta de 2,392 observaciones y 15 columnas, las cuales son:

- **id_estudiante**: Identificador único del estudiante.
- **edad**: Edad del estudiante.
- **género**: Género del estudiante (0: Masculino, 1: Femenino).
- **etnia**: Origen étnico del estudiante (0: Caucásico, 1: Afroamericano, 2: Asiático, 3: Otros).
- **educación_padres**: Nivel de educación de los padres.
- **tiempo_estudio_semanal**: Horas semanales dedicadas al estudio.
- **ausencias**: Número de ausencias del estudiante.
- **tutorías**: Indica si el estudiante recibe tutorías (0: No, 1: Sí).
- **apoyo_padres**: Nivel de apoyo recibido por los padres.
- **extra_curricular_otro**: Participación en actividades extracurriculares distintas a las mencionadas.
- **extracurricular_deportes**: Participación en deportes.
- **extracurricular_música**: Participación en actividades musicales.
- **extracurricular_voluntariado**: Participación en actividades de voluntariado.
- **promedio**: Promedio de las calificaciones del estudiante.
- **calificación**: Clasificación del estudiante basada en el promedio.

## 📚 Librerías Utilizadas

Para llevar a cabo este análisis, hemos utilizado las siguientes librerías de Python:

- **pandas**: Para el tratamiento y manipulación de datos.
- **numpy**: Para operaciones numéricas.
- **scipy**: Para cálculos estadísticos.
- **matplotlib**: Para la generación de gráficos.
- **seaborn**: Para la visualización de datos.

## 📊 Análisis Exploratorio de Datos

### 1. Ingesta de Datos
Se ha realizado la ingesta de los datos desde un archivo CSV utilizando pandas.

### 2. Resúmenes de Datos
Se obtuvieron resúmenes descriptivos de los datos para comprender sus principales características.

### 3. Preparación de Datos

#### 3.1 Valores Faltantes
Se comprobó que el conjunto de datos no presenta valores faltantes.

#### 3.2 Valores Duplicados
Se verificó que no hay valores duplicados según la variable `id_estudiante`.

#### 3.3 Transformación de Características
Se realizaron las siguientes conversiones de variables categóricas:

- **género**: Convertido a categorías 'masculino' y 'femenino'.
- **etnia**: Convertido a categorías 'caucasico', 'afroamericano', 'asiatico' y 'otro'.
- **educación_padres**: Convertido a categorías 'ninguno', 'escuela_secundaria', 'formacion_universitaria', 'licenciatura' y 'mas_alto'.
- **tutorías**: Convertido a categorías 'no' y 'si'.
- **apoyo_padres**: Convertido a categorías 'ninguno', 'bajo', 'moderado', 'alto' y 'muy_alto'.
- **extra_curricular_otro**, **extracurricular_deportes**, **extracurricular_música** y **extracurricular_voluntariado**: Convertido a categorías 'no' y 'si'.
- **calificación**: Convertido a letras correspondientes al promedio ('A', 'B', 'C', 'D', 'F').

## 🧠 Conocimientos Aplicados

En este análisis, se han aplicado conocimientos avanzados en:

- **Análisis Exploratorio de Datos (EDA)**: Identificación de valores faltantes, nulos y atípicos.
- **Tratamiento de Datos**: Transformación y preparación de datos para su análisis.
- **Estadística**: Utilización de técnicas estadísticas para comprender las relaciones entre variables.
- **Visualización de Datos**: Generación de gráficos y visualizaciones para interpretar los datos.
- **Limpieza de Datos**: Eliminación de valores duplicados y conversión de variables categóricas.

## 📬 Contacto

Para cualquier consulta o comentario, pueden contactarme a través de LinkedIn en el siguiente enlace: [LinkedIn](www.linkedin.com/in/andersoncrs) o a través del correo electrónico: andersoncamilo.rodriguez.s@gmail.com.

## 📜 Licencia
Este proyecto está bajo la licencia [Apache 2.0](LICENSE).

---
 😁 Espero que este informe haya sido de utilidad y les permita comprender mejor los factores que influyen en el rendimiento académico de los estudiantes. ¡Gracias por su atención!