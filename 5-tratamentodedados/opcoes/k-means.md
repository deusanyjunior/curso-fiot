# K-means clustering

- Tipo de aprendizado: Não-supervisionado
- Subcategoria: Clusterização
- Autoria: MacQueen, 1967

## Descrição

### Onde é usado (tecnicamente)

Utilizado para organizar dados em grupos de similaridade.

### Como é utilizado

![K-Means](imgs/k-means.png)

Não precisa de um conjunto de treinamento rotulado, ou seja, não há indicação a priori de quais dados pertencem a quais grupos.

Como um algoritmo de aprendizado não-supervisionado, como não há exemplos do que seria esperado, a avaliação pode ser mais difícil que o aprendizado supervisionado.
Usualmente, a qualidade do agrupamento obtido está relacionado à maximização da distância inter-cluster (entre pontos de dados de clusters diferentes) e minimização da distância intra-cluster (dentro de um mesmo cluster, a ideia é que a distância entre os pontos de dados seja minimizada).

Seu hiperparâmetro (uma configuração do algoritmo de agrupamento) é o número de clusters k (número de grupos de dados), que pode ser obtido experimentalmente, a depender da aplicação.

Começa com centroides (centros dos agrupamentos) atribuidos de forma aleatória, e então reagrupa os dados e centroides até que um critério de parada seja atingido.
Critério de parada: quando há reclassificação mínima dos dados a diferentes clusters, ou quando há mínima mudança nos centroides.

![K-Means Convergence](imgs/K-means_convergence.gif)

Como pontos positivos, é simples de implementar e de entender, eficiente e algoritmo de aprendizado não-supervisionado mais popular.

Como pontos negativos, o usuário precisa especificar k (número de grupos de dados), o algoritmo é sensível a outliers (pontos "fora da curva"), e não é indicado para agrupar dados cujos agrupamentos tenham formato não-convexo.

### Exemplos de caso de uso

Agrupar documentos de acordo com diferentes critérios, agrupamento de clientes, agrupamento de registros de pedidos de call center.

## Referências

[MacQueen, 1967](https://www.semanticscholar.org/paper/Some-methods-for-classification-and-analysis-of-MacQueen/ac8ab51a86f1a9ae74dd0e4576d1a019f5e654ed)

[K-means use cases](https://dzone.com/articles/10-interesting-use-cases-for-the-k-means-algorithm)

[K-Means GIF](https://commons.wikimedia.org/wiki/File:K-means_convergence.gif)
