# AdaBoost

- Tipo de aprendizado: Supervisionado
- Subcategoria: Classificação
- Autoria: Yoav Freund e Robert Schapire

## Descrição

### Onde é usado (tecnicamente)

Utilizado para classificações, principalmente em casos onde amostras contém muitas variáveis. Pode ser usado com outros algoritmos, melhorando a performance.

### Como é utilizado

Um conjunto de treinamento é usado para gerar uma floresta de árvores de decisão curtas, que geralmente só usam uma viariável. Essas árvores, que são considerados "classificadores ruins", recebem pesos diferentes para a importância da classificação final. Cada nova árvore gerada leva em consideração o erro da árvore anterior.

![Cada clasisficador recebe um peso, de acordo com o anterior[2]](imgs/adaboost.png)

### Exemplos de caso de uso

Detecção de pedestres, detecção de rostos[3], detecção de microcalcificações em cancer de mama[4].

## Referências

[1. What is AdaBoost Algorithm – Model, Prediction, Data Preparation](https://data-flair.training/blogs/adaboost-algorithm/)

[2. AdaBoost, Clearly Explained](https://www.youtube.com/watch?v=LsK-xG1cLYA&app=desktop)

[3. Boosting: Algorithms and Application](http://users.cecs.anu.edu.au/~wanglei/SPR_course/boosting.pdf)

[4. ANN and Adaboost application for automatic detection ofmicrocalcifications in breast cancer](https://reader.elsevier.com/reader/sd/pii/S0378603X16301668?token=5416CCA3E5CD2754CFD6A50DB583C102F0E79273CE3F18BBD6150F456AFC76F18BFACDBF7163602CEC0035F0CF400A7B)