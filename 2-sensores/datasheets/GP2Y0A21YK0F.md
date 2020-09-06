# GP2Y0A21YK0F

- Classificação: Sensor de medição de distância
- Nome técnico: Sharp GP2Y0A21YK0F

O GP2Y0A21YK0F é uma unidade de sensor de medição de distância, composta por uma combinação integrada de detector sensível à posição, diodo de infravermelho e circuito de processamento de sinal.
A variedade da refletividade do objeto, a temperatura ambiente e a duração da operação não são influenciadas facilmente para a detecção da distância devido à adoção do método de triangulação.
Este dispositivo emite a tensão correspondente à distância de detecção. Portanto, este sensor também pode ser usado como um sensor de proximidade.

## Características

- Faixa de medição de distância: 10 a 80 cm
- Tipo de saída: Analógica
- Tamanho: 29,5 × 13 × 13,5 mm
- Corrente: Tipicamente 30 mA
- Tensão de alimentação: 4,5 até 5,5 V
- Temperatura de Operação: -10 até +60 °C
- Temperatura de Armazenagem: -40 até +70 °C 

### Sensibilidade

Como o sensor e analogo, não há uma sensibilidade especifica. 

### Faixa

A faixa do sensor especificada é de 10 cm até 80 cm, porem segundo Malheiros et. al. demostra usabilidade a partir de 8 cm.

### Precisão

Segundo Malheiros et al. o sensor demostra um desvio padrão na tensão de saida de 0,030 mV, indiferentemente da distancia do objeto. A tensão de saida varia entre 3 V para 8 cm e 0,4 V para 80 cm. Dado uma precisão de 99,9% (sendo 3,09 desvios) a precisão varia entre +/- 0,25 cm para 8 cm e +/- 18,54 cm para 80 cm.

### Exatidão

A exatidão da medição varia em função de dois fatores: O ângulo da superfície e a direção de movimento do objeto.

Dependendo do ângulo e da distância da superfície a exatidão da medição varia conforme a imagem embaixo.

![Exatidão do Sensor em função do ângulo e da distância da superfície](./imgs/GP2Y0A21YK0F_Exatidao_Angulo.png)

Além disso existe uma dependência entre a direção de movimento do objeto e da posição do sensor, ilustrado na seguinte imagem.

![Direção de movimento correto e errado](./imgs/GP2Y0A21YK0F_Posicao.png)

O posicionamento do sensor diretamente influencia a exatidão, especialmente se ha um ângulo entre a superfície e o sensor.

![Direção de movimento correto e errado](./imgs/GP2Y0A21YK0F_Exatidao_Posicao.png)

### Resolução

Como o sensor não tem saída digital, não há uma resolução especifica.

### Offset

O sensor não tem um offset especificado por demostrar uma saida instavél entre 0-8 cm e pelo comportamento altamente não linear (veja a abaixo). 

### Linearidade

O sensor tem um comportamento altamente não linear. 

![Não linearidade entre tensão de saída e distância do objeto](./imgs/GP2Y0A21YK0F_Linearidade.png)

### Histerese

### Tempos de resposta

### Linearidade dinâmica

## Fotos

## Referências

[Datasheet GP2Y0A21YK0F](https://global.sharp/products/device/lineup/data/pdf/datasheet/gp2y0a21yk_e.pdf)

[Malheiros, P., Gonc¸alves, J., and Costa, P. (2009). Towards a more Accurate Infrared Distance
Sensor Model. In International Symposium on Computational Intelligence for Engineering
Systems., Porto](https://pdfs.semanticscholar.org/8d5d/4d42800577d6fba17208f31046f39feaff30.pdf)

