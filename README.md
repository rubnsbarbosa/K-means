# K-means
The K-means is the most well-known clustering algorithm and was proposed by Stuart Lloyd at Bell Labs in 1957. It is used to find clusters which doesn't have been explicitly labeled in the dataset and to find patterns.

# Algorithm

#### Input:
```
- Training set  
- K - (number of clusters)
```

#### Algorithm:
```
- Randomly initialize K cluster centroids  
```

```python
repeat {
    for i = 1 to m,
        c(i) := index from (1 to K) of cluster centroid closest to x(i)
    for k = 1 to K,
        mu(k) := average (mean) of points assigned to cluster k
}
```

## Visualize the randomly initialize cluster centroids

![Captura de Tela 2020-05-08 às 14 22 36](https://user-images.githubusercontent.com/17646546/81434199-31ee7d80-913c-11ea-8d39-d42da329d460.png)

## Visualize the cluster centroids optimized

![Captura de Tela 2020-05-08 às 14 22 50](https://user-images.githubusercontent.com/17646546/81434318-58acb400-913c-11ea-9454-1d47518883bf.png)

## Visualize in 3D

![Captura de Tela 2020-05-08 às 14 22 59](https://user-images.githubusercontent.com/17646546/81434375-6d894780-913c-11ea-8de3-4da82f175310.png)
