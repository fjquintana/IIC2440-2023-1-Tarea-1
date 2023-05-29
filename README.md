# IIC2440-2023-1-Tarea-1
Repositorio para la tarea 1 de IIC2440 - Procesamiento de Datos Masivos.

Integrantes:
- Rodrigo Nahum
- Fernando Quintana

# Codigo
El repositorio cuenta con dos notebooks, `LSH.ipynb` y `similar_people.ipynb`.

## LSH.ipynb
En este notebook, procesamos los tweets, y hacemos LSH para obtener pares de tweets similares. Para correr este notebook, se requiere tener el `csv` con los tweets. Usamos shingles y hacemos LSH como visto en clases, usando permutaciones y viendo el primer shingle de cada texto segun cada permutacion. Luego, amplificando usando bandas y rondas por banda. Con esto, obtenemos pares de tweets similares.

## similar_people.ipynb
En este notebook, usando los tweets similares computados, obtenemos personas que tweetean de forma similar. Para esto, contamos la cantidad de tweets parecidos entre dos usuarios, y decidimos si esto es suficiente para decir que dos usuarios son parecidos, basado en distintos umbrales definidos.
