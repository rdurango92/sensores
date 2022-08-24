# Sensorización y Machine Learning 🤖
"Sensorización y Machine Learning - Clasificación de series de tiempo"

---

## Tabular Playground Series - Apr 2022  

Esta fue una competencia en la plataforma [**Kaggle**](https://www.kaggle.com/competitions/tabular-playground-series-apr-2022), y en este notebook presento mis hallazgos.

---

## 📃| **Introducción**

Con el auge de la industria 4.0, hoy las personas que trabajamos en la industria tenemos más datos que nunca, esto nos ha puesto nuevos retos para tomar decisiones acertadas basados en la inmensa cantidad de datos que se generan día a día, y nos ha exigido mejorar nuestras habilidades y explorar nuevas herramientas como el análisis de datos y el machine learning, este es un ejemplo de uso. 

Se nos han proporcionado miles de secuencias (cada una de sesenta segundos de duración) leídas por sensores biológicos, estos registraron a cientos de participantes que podrían haber estado en cualquiera de dos posibles estados de actividad. ¿Podemos predecir en qué estado se encontrará un participante a partir de los datos de los sensores?

## 🔢| **Objetivos**

Construir un modelo de machine learning de clasificación de series de tiempo, que pueda predecir el estado de un participante (0 o 1) basado en la lectura que hacen 12 sensores durante 60 segundos. 

## 🎯| **Conclusión**

Logramos construir un modelo de clasificación bastante eficiente con una excelente capacidad de generalización, fue bastante importante hacer un buen proceso de ingeniería de datos, pues gracias a ello pudimos detectar predictores que no suelen ser muy usados (como la kurtosis) pero que pueden ser una gran fuente de información. 
Finalmente, el objetivo de este análisis era mostrar que haciendo un uso inteligente de los datos disponibles podemos extraer mucho valor, depende de nosotros pensar en formas creativas para usar extraer conocimiento de estos. Estoy seguro de que con el paso del tiempo tendremos a nuestra disposición mas y mas datos, y por ello es importante visibilizar y dar uso a estas metodologías antes que nos veamos abrumados por el volumen de datos. 
