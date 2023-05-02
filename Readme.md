![UPC](https://github.com/BinaryCode-wave/Parcial/blob/main/imgs/UPC.png)
# Recomendaciones Personalizadas Musicales empleando Teoría de Grafos

Este proyecto tiene como objetivo brindar recomendaciones de canciones personalizadas y precisas a los usuarios, utilizando grafos y algoritmos para analizar su actividad y encontrar patrones relevantes con el fin de mejorar su experiencia. Se empleará la Teoría de Grafos y el algoritmo de Dijkstra para el desarrollo de una aplicación que brinde de manera personalizada recomendaciones de música.

## Integrantes

### Huaman Huaranga Lennin Daniel
![Lennin Huaman](https://github.com/BinaryCode-wave/Parcial/blob/main/imgs/contributors/Lennin.png)


### Mendoza Ramos Dominik Aldahir Alexis
[![Dominik Mendoza](https://github.com/BinaryCode-wave/Parcial/blob/main/imgs/contributors/Dominik.png)](https://www.linkedin.com/in/dominik-mendoza-ramos-91496a224/)


### Ramirez Mendoza Carlos Arian
![Arian Ramirez](https://github.com/BinaryCode-wave/Parcial/blob/main/imgs/contributors/Arian.png)


## Descripción del problema

La música es una parte fundamental de la vida de muchas personas, y las plataformas de streaming como Spotify y YouTube permiten un fácil acceso a una amplia variedad de canciones y artistas. Sin embargo, a menudo es difícil encontrar nueva música que se adapte a los gustos personales de cada individuo. Ante ello surge la necesidad de muchas personas de descubrir nueva música que se adapte a sus gustos personales. Además, este proyecto también tiene implicaciones más amplias en la industria de la música, ya que las recomendaciones personalizadas pueden mejorar la experiencia del usuario y aumentar la fidelidad del cliente.

## Conjunto de datos

El conjunto de datos consta de un total de 26 variables para cada una de las canciones, entre las cuales se encuentran el nombre de la canción, el nombre del artista, el enlace de la canción en Spotify y su correspondiente álbum, la duración de la canción, el tempo, la tonalidad, la energía, la valencia, la instrumentación, la presencia de público en la grabación, el número de streams y el enlace al video de Youtube.

## Representación mediante grafos

Los nodos están representados por el ID de las canciones y para el peso de cada arista se realizó el cálculo de la distancia euclidiana entre los valores de 'Danceability', 'Loudness', 'Speechiness', 'Acousticness', 'Instrumentalness', 'Liveness', 'Valence' y 'Tempo' de una canción en específico. Se han generado dos representaciones en grafos utilizando las herramientas Graphviz y Gephi, con 30 nodos y 22 aristas y 1600 nodos y 25135 aristas, respectivamente.

### Grafo con 30 nodos y 22 aristas
![graph30](https://github.com/BinaryCode-wave/Parcial/blob/main/imgs/Graph30.png)

### 1600 nodos y 25135 aristas

![graph1600](https://github.com/BinaryCode-wave/Parcial/blob/main/imgs/Graph1600Nodes.png)

## Propuesta

Se propone el uso de la Teoría de Grafos y el algoritmo de Dijkstra para el desarrollo de una aplicación que brinde de manera personalizada recomendaciones de música a los usuarios, utilizando la información recopilada de la plataforma de streaming musical Spotify. Se buscará analizar la actividad de los usuarios y encontrar patrones relevantes para mejorar su experiencia y aumentar la fidelidad del cliente.