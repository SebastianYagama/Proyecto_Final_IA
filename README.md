# Clasificador por generos musicales
## Lista de los integrantes del grupo:
- Jhon Sebastian Yagama.

## Introducción:
- En este proyecto se realiza un clasificador por géneros musicales en Python utilizando un modelo de aprendizaje supervisado y aplicando los conocimientos adquiridos en el curso, El conjunto de datos seleccionado tiene un total de 1000 pistas de audio, cada una con una duración de 30 segundos y se dividen en 10 géneros, los cuales son Blues, Country, Hiphop, Metal, Reggae, Classical, Disco, Jazz, Pop y Rock. Esto quiere decir que de cada genero hay 100 pistas de audio, cada pista es un archivo de audio mono de 16 bits a 22050Hz en formato.wav.
- Adicionalmente el Dataset incluye 2 archivos .csv para 3 y 30 segundos, los cuales contienen una tabla que tiene 1000 filas correspondientes a los 10 géneros por 100 archivos de audio y 60 columnas que corresponden a las características, entre estas características esta la tasa de cruce por cero, armónicos y perceptual, los Beats por minuto, el centroide espectral, el descenso espectral, los coeficientes cepstrales de frecuencia Mel y las frecuencias cromáticas.

- Dataset utilizado: https://www.kaggle.com/andradaolteanu/gtzan-dataset-music-genre-classification

## Desarrollo:
- Para resolver este problema se siguieron una serie de pasos, se inicia con el procesamiento del conjunto de datos o limpieza, se debe realizar la normalización y una reducción dimensional, luego la selección de las métricas de evaluación para posteriormente seleccionar el mejor modelo de aprendizaje supervisado y realizar la optimización de hiperparámetros, que permitirán finalmente entregar resultados. 

## Resultados
- Tabla de los resultados de las mediciones para cada modelo.
![Tabla2](https://user-images.githubusercontent.com/88201271/171976921-447fd973-5eb0-45d5-8210-e566246f104d.PNG)
Tal como se puede observar en la tabla se obtuvo que el mejor modelo para dar solución a la problemática es Random Forest el cual se seleccionó, sin embargo, también hay métodos con buenos resultados como lo son knnvecinos más cercanos y máquinas de vectores de soporte. Por otro lado, el peor método en este caso para dar solución al problema es Naive Bayes.

- Matriz de confusión.
![Tabla1](https://user-images.githubusercontent.com/88201271/171976937-36c0f88e-ca66-4271-af8c-1e1242017b50.png)
En la anterior tabla se puede observar la matriz de confusión, donde se muestra de manera grafica el desempeño del algoritmo al observar a detalle los aciertos y errores que presenta el modelo a la hora de pasar por el proceso de aprendizaje con los datos.

## Conclusiones
- La matriz de confusión implementada permite ver de una mejor manera el rendimiento del algoritmo seleccionado y a su vez permite identificar de manera clara los errores y los aciertos, lo cual es muy importante porque crea una oportunidad de mejora a futuro.
- Seleccionar adecuadamente el algoritmo que se utilizara para dar solución a la problemática es muy importante, ya que como se pudo observar al hacer la comparación los resultados pueden variar bastante. 

## Link al video de YouTube:
- 
