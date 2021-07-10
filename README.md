# geolocation_clustering_kmeans
Geolocation Clustering using the k-means Algorithm

O problema consiste em agrupar os dados (coordenadas de latitude e longitude) com base na sua geolocalização e respeitando as restrições.

Restrição: 

1) Distância máxima de 1.6km entre os pontos e seu centróide.

A figura abaixo mostra os pontos em azul antes do agrupamento com o algoritmo kmeans.


![image](https://user-images.githubusercontent.com/18504119/120047713-9e5c4900-bfeb-11eb-8fc3-3af8911081b7.png)


A figura abaixo demonstra o resultado: clusters com cores diferentes e centróides com um marcador preto.
Entretanto, utilizando o algoritmo Kmeans, não foi possível respeitar a restrição da distância de 1.6km entre os pontos.


![image](https://user-images.githubusercontent.com/18504119/120046912-9c918600-bfe9-11eb-93d5-cab654b217bf.png)


Installation: 
pip install folium
