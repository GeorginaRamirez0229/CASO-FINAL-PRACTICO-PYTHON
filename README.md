**Análisis de Tuberculosis con Python**
Este proyecto consiste principalmente en el análisis de datos sobre la tuberculosis (TB) utilizando la herramienta de Python, enfocado en la limpieza, transformación y visualización de datos para obtener información relevante sobre la incidencia de la enfermedad.

**Descripción del proyecto**
La tuberculosis es una enfermedad infecciosa causada por Mycobacterium tuberculosis, que afecta principalmente a los pulmones. En este proyecto se trabaja con datos de la OMS y población para analizar:

***1.Casos de tuberculosis por país y año***

***2.Distribución por género, edad y tipo de diagnóstico***

***3.Tasa de incidencia por cada 100,000 habitantes***

***4.Tendencias a lo largo del tiempo***

📂***Fuentes de datos***
1. who.csv: Datos de casos de tuberculosis
2. population.csv: Datos de población por país y año

⚙️***Tecnologías utilizadas***
Python, Pandas, NumPy, entre otras

***Procesamiento de datos***
Se realizaron las siguientes etapas:

1. ***Limpieza de datos***: Corrección de valores faltantes (ej. Namibia “NA”), sustitución de valores nulos por 0 y verificación de consistencia

2. ***Transformación***: Uso de melt para convertir columnas en filas
Creación de nuevas variables: Género (Masculino / Femenino), Método de diagnóstico:SP (Smear Positive), SN (Smear Negative), EP (Extrapulmonary), REL (Relapse), Grupo de edad

3. ***Integración***: Unión de datasets para incluir población

**Creación del dataset final**: tuberculosis.csv
***Análisis realizado*** Distribución de casos:
1.Por género

2.Por método de diagnóstico

3.Por grupo de edad

***Métricas clave***: Número de países analizados y Año inicial y final del estudio

***Tasa de incidencia***: Se calculó mediante la fórmula:
Tasa de incidencia = (casos / población) * 100,000
Por país y año
Global por año

**Visualizaciones**
Se generaron gráficas como:
📉 Tasa de incidencia por año (Seaborn)
📊 Gráficas interactivas (Plotly)
🚀 Resultados

**El análisis permite**: Identificar tendencias de la tuberculosis a nivel global, comparar incidencia entre años, analizar grupos más afectados
y entender el impacto según tipo de diagnóstico
