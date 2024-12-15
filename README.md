# Análisis y Simulación de Distribuciones en Crowdshipping

## Descripción General

Este repositorio contiene los resultados de dos proyectos relacionados con la simulación y análisis estadístico de un sistema de entrega de paquetes en una ciudad basado en el modelo de *Crowdshipping*. Los proyectos tienen como objetivos principales el análisis de distribuciones de datos simulados y la evaluación del cumplimiento de teorías estadísticas aplicadas al campo de la ingeniería.

### Proyecto 1: **Análisis Descriptivo del Tiempo entre Llegadas**

Este proyecto se centra en analizar las distribuciones de los tiempos entre llegadas de paquetes y viajeros en el sistema de Crowdshipping. Se trabajó con datos generados mediante un simulador, y se realizó un análisis descriptivo y exploratorio con herramientas estadísticas y de visualización.

**Metodología:**

- Lectura y limpieza de datos simulados.
- Separación de los datos por origen y destino.
- Cálculo de tiempos entre llegadas para paquetes y viajeros.
- Análisis estadístico descriptivo (media, mediana, desviación estándar, asimetría, curtosis, etc.).
- Comparación de distribuciones con pruebas de bondad de ajuste (Kolmogorov-Smirnov).

**Resultados principales:**

- Las distribuciones de tiempos entre llegadas mostraron un sesgo positivo, ajustándose mejor a una distribución exponencial.
- La variabilidad fue mayor en los tiempos entre llegadas de paquetes que en los de viajeros.
- Se generaron histogramas, diagramas de cajas y mapas de calor que ilustran la dinámica del sistema.

---

### Proyecto 2: **Distribuciones de Muestreo y Pruebas de Hipótesis**

Este proyecto se orienta a evaluar empíricamente conceptos clave como el Teorema del Límite Central y el riesgo en pruebas de hipótesis mediante el análisis de distribuciones de muestreo derivadas de los datos originales.

**Metodología:**

- Extracción de muestras aleatorias de tamaño fijo (n=50) de los datos originales.
- Cálculo de medias muestrales y descripción de sus distribuciones.
- Comparación entre la distribución de las medias muestrales y la distribución original.
- Pruebas de hipótesis para evaluar si el tiempo promedio entre llegadas era de 2 segundos, considerando distintos escenarios.

**Resultados principales:**

- Se observó una transición a distribuciones normales en las medias muestrales, evidenciando el Teorema del Límite Central.
- La hipótesis de que el tiempo promedio entre llegadas es de 2 segundos fue rechazada en el 100% de las pruebas, indicando tiempos de llegada significativamente menores.

---

## Archivos incluidos

- **Reporte de resultados**: Documentación detallada de cada paso y análisis realizado.
- **Notebook**: Código Python utilizado para simulación, análisis y visualización.
- **Gráficos**: Mapas de calor y representaciones visuales de las distribuciones.
- **Archivos CSV**: Datos procesados para análisis, incluyendo conteos por origen-destino.

## Herramientas utilizadas

- Lenguaje de programación: Python.
- Librerías principales: Pandas, NumPy, Matplotlib, Seaborn, Scipy.
- Simulador: Software desarrollado para modelar el sistema de Crowdshipping.

## Conclusión

Ambos proyectos destacan la utilidad de la simulación computacional y el análisis estadístico en la optimización de sistemas logísticos. Los resultados muestran la viabilidad del modelo de Crowdshipping y evidencian aspectos clave para su optimización futura.
