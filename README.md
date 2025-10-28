Análisis de Salarios de Trabajos en Ciencia de Datos

Introducción

Este proyecto consiste en un Análisis Exploratorio de Datos (EDA) sobre una base de datos de salarios en el campo de la Ciencia de Datos. El objetivo principal es comprender las posibles ganancias y la expectativa salarial a nivel mundial para los profesionales de esta área.

Tarea Principal

Elaborar un Jupyter Notebook que abarque un EDA básico. Este análisis se enfoca en el estudio univariado y la exploración bivariada, aprovechando las capacidades de manipulación y visualización de datos en Python.

Estructura del Proyecto

El análisis se divide en tres fases principales:

    Introducción: Presentación del objetivo y las variables a analizar.

    Preparación: Carga, limpieza y comprensión inicial de los datos.

    Análisis Exploratorio de Datos (EDA): Análisis univariado, bivariado y exploración de relaciones intuitivas entre las variables.

Análisis Exploratorio de Datos (EDA)

El EDA incluyó:

    Análisis Univariado: Distribución de salarios por año y salarios promedio por país.

    Análisis Bivariado: Exploración de salarios por título de trabajo.

    Relaciones Intuitivas: Distribución de salarios y trabajo remoto en función de:

        Año de trabajo

        Nivel de experiencia

        Tipo de empleo

        Residencia del empleado

        Ubicación y tamaño de la empresa

Conclusiones Clave (Matriz de Correlación)

El análisis de correlación de Pearson arrojó las siguientes observaciones para el salary_in_usd:

    Existe una correlación positiva significativa con el año de trabajo (work_year) y el nivel de experiencia (experience_level). Esto sugiere que a mayor experiencia y con el paso del tiempo, los salarios tienden a ser más altos.

    Existe una correlación negativa significativa con el porcentaje de trabajo remoto (remote_ratio), indicando que los salarios tienden a disminuir a medida que aumenta la proporción de trabajo a distancia.

    El tamaño de la empresa (company_size) no mostró una correlación significativa con el salario.

Tecnologías Utilizadas

Este proyecto se desarrolló íntegramente en un Jupyter Notebook utilizando las siguientes librerías de Python:

    Pandas: Para la carga, manipulación y análisis de datos.

    NumPy: Para el soporte de cálculos numéricos eficientes.

    Matplotlib y Seaborn: Para la creación de gráficos estadísticos y visualizaciones.

    Plotly: Para la generación de gráficos interactivos (como el de salarios por especialidad).

Diccionario de Datos

Columna	Descripción
work_year	Año de trabajo
experience_level	Nivel de experiencia del empleado en el puesto
employment_type	Tipo de empleo
job_title	Título del trabajo
salary	Salario bruto anual
salary_currency	Moneda del salario
salary_in_usd	Salario convertido a USD
employee_residence	Residencia del empleado
remote_ratio	Porcentaje de trabajo remoto
company_location	Ubicación de la empresa
company_size	Tamaño de la empresa

Fuente de la Base de Datos: Link a la base de datos.

Autor

Desarrollado por: Josué Jair Pelagio Monroy
