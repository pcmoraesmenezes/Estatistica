# Medidas Descritivas

Após os dados estarem organizados e apresentados por meio de tabelas e gráficos, é necessário analisá-los. Para isso, utilizamos as medidas descritivas.

Elas são:

-   Média

-   Mediana

-   Moda

Medidas de variabilidade ou dispersão:

-   Variância

-   Desvio Padrão

-   Coeficiente de Variação

Medidas de posição:

-   Quartis

-   Decis

-   Percentis

## Medidas de Posição

Procuram sintetizar as informações em um único valor informativo.

Tem a tendencia de se posicionar no centro da distribuição dos dados.

### Média

É a soma de todos os valores dividido pelo número de valores.

$$\bar{x} = \frac{\sum_{i=1}^{n} x_i}{n}$$

-   Quando se tem valores extremos na distribuição, a média é afetada.

-   Na sua determinação são considerados todos os dados

-   É única

-   É a medida mais utilizada

Exemplo:

| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |
|---|---|---|---|---|---|---|---|---|----|
|   |   |   |   |   |   |   |   |   |    |

$$\bar{x} = \frac{1+2+3+4+5+6+7+8+9+10}{10} = 5.5$$

### Mediana

É o valor que divide a distribuição em duas partes iguais.

-   Quando se tem valores extremos na distribuição, a mediana não é afetada.

-   Na sua determinação são considerados todos os dados

-   Não é única

-   É a medida mais utilizada

Exemplo:

| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |
|---|---|---|---|---|---|---|---|---|----|
|   |   |   |   |   |   |   |   |   |    |

$$\bar{x} = \frac{5+6}{2} = 5.5$$

Note que o numero de elementos é par, então a mediana é a média dos dois elementos centrais.

Exemplo:

| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 |
|---|---|---|---|---|---|---|---|---|
|   |   |   |   |   |   |   |   |   |

$$\bar{x} = 5$$

Note que o numero de elementos é impar, então a mediana é o elemento central.

### Moda

É o valor que ocorre com maior frequência na distribuição.

-   Quando se tem valores extremos na distribuição, a moda não é afetada.

-   Na sua determinação são considerados todos os dados

-   Não é única

-   É a medida mais utilizada

Exemplo:

| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |
|---|---|---|---|---|---|---|---|---|----|
|   |   |   |   |   |   |   |   |   |    |

Nesse caso como nenhuma moda se repete, dizemos que a distribuição é amodal.

Exemplo:

| 1 | 1 | 2 | 2 | 5 | 6 | 7 | 8 | 9 | 10 |
|---|---|---|---|---|---|---|---|---|----|
|   |   |   |   |   |   |   |   |   |    |

Nesse caso a moda é 1 e 2.

Exemplo:

| 1 | 1 | 2 | 2 | 5 | 5 | 7 | 8 | 9 | 10 |

Nesse caso a moda é 1, 2 e 5.

### Propriedades da média, mediana e moda:

-   Quando a distribuição é simétrica, a média, mediana e moda coincidem.

-   Quando a distribuição é assimétrica, a média é afetada, a mediana não é afetada e a moda é afetada.

-   Quando a distribuição é bimodal, a média é afetada, a mediana é afetada e a moda não é afetada.

-   Quando a distribuição é multimodal, a média é afetada, a mediana é afetada e a moda não é afetada.

Tabela:

| | Média | Mediana | Moda |
|---|---|---|---|
|Vantagens| - É a medida mais utilizada <br> - É única | - Não é afetada por valores extremos <br> - Não é afetada por valores extremos | - Não é afetada por valores extremos <br> - Não é afetada por valores extremos |
|Desvantagens| - É afetada por valores extremos | - Não é única <br> - É afetada por valores extremos | - Não é única <br> - É afetada por valores extremos |

## Medidas de Variabilidade ou Dispersão

### Amplitude Total

É a diferença entre o maior e o menor valor da distribuição.

$$A = x_{max} - x_{min}$$

-   É afetada por valores extremos

-   Não é única

Exemplo:

| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |

$$A = 10 - 1 = 9$$

Exemplo:

| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 |

$$A = 9 - 1 = 8$$

### Variância e Desvio Padrão

A variância é a média dos quadrados dos desvios em relação à média.

$$s^2 = \frac{\sum_{i=1}^{n} (x_i - \bar{x})^2}{n-1}$$

O desvio padrão é a raiz quadrada da variância.

$$s = \sqrt{\frac{\sum_{i=1}^{n} (x_i - \bar{x})^2}{n-1}}$$

-   É afetada por valores extremos

-   Não é única

Exemplo:

| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |

$$\bar{x} = 5.5$$

$$s^2 = \frac{(1-5.5)^2 + (2-5.5)^2 + (3-5.5)^2 + (4-5.5)^2 + (5-5.5)^2 + (6-5.5)^2 + (7-5.5)^2 + (8-5.5)^2 + (9-5.5)^2 + (10-5.5)^2}{10-1} = 8.25$$

$$s = \sqrt{8.25} = 2.872$$

### Desvios em relação à média

| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |

$$\bar{x} = 5.5$$

| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |

$$x_i - \bar{x}$$

| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |

$$(x_i - \bar{x})^2$$


### Coeficiente de Variação

É a razão entre o desvio padrão e a média.

$$CV = \frac{s}{\bar{x}}$$

-   É afetada por valores extremos

-   Não é única

Exemplo:

| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |

$$\bar{x} = 5.5$$

$$s = 2.872$$

$$CV = \frac{2.872}{5.5} = 0.522$$

### Errro Padrão da Média

É a razão entre o desvio padrão e a raiz quadrada do número de elementos.

$$EP = \frac{s}{\sqrt{n}}$$

-   É afetada por valores extremos

-   Não é única

Exemplo:

| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |

$$\bar{x} = 5.5$$

$$s = 2.872$$

$$EP = \frac{2.872}{\sqrt{10}} = 0.908$$

### MEdidas de Separatriz(Quartis, Decis e Percentis)

São medidas que dividem a distribuição em partes iguais.

-   Quartis: Dividem a distribuição em 4 partes iguais.

-   Decis: Dividem a distribuição em 10 partes iguais.

-   Percentis: Dividem a distribuição em 100 partes iguais.

### Quartis

-   Q1: 25% dos dados são menores que Q1.

-   Q2: 50% dos dados são menores que Q2.

-   Q3: 75% dos dados são menores que Q3.

-   Q4: 100% dos dados são menores que Q4.

Exemplo:

| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |

$$Q1 = 2.5$$

$$Q2 = 5.5$$

$$Q3 = 7.5$$


O calculo dos quartis é feito da seguinte forma:

$$Q1 = \frac{n+1}{4}$$

$$Q2 = \frac{2(n+1)}{4}$$

$$Q3 = \frac{3(n+1)}{4}$$

### Boxplot

É um gráfico que representa os quartis.

Fornece informações sobre a simetria da distribuição.

## Exercícios

1. Seja os dados abaixo referentes à taxa de proteína (g/kg) na carne de suínos analisadas em 18 amostras.

| 10,0 | 10,4 | 10,7 | 11,4 | 11,6 | 12,2 |
|------|------|------|------|------|------|
| 12,2 | 12,4 | 12,4 | 12,5 | 13,4 | 13,5 |
| 13,9 | 14,0 | 14,6 | 15,0 | 15,3 | 15,6 |

a) Calcule a média, mediana e moda.

b) Calcule a amplitude total.

c) Calcule a variância e o desvio padrão.

d) Calcule o coeficiente de variação.

e) Calcule o erro padrão da média.

f) Calcule os quartis.

g) Calcule e interprete o quartil 1, quartil 3.

h) Que porcentagem de amostras apresentam taxa de proteína inferior a 12,4 g/kg?

Não oculte os calculos

## Respostas

1. a) Média = 12,7; Mediana = 12,4; Moda = 12,4 e 12,2

   b) Amplitude Total = 5,6

   c) Variância = 4,4; Desvio Padrão = 2,1

   d) Coeficiente de Variação = 0,17

   e) Erro Padrão da Média = 0,5

   f) Q1 = 11,6; Q2 = 12,4; Q3 = 14,6

   g) 25% das amostras apresentam taxa de proteína inferior a 11,6 g/kg e 75% das amostras apresentam taxa de proteína inferior a 14,6 g/kg.

   h) 50% das amostras apresentam taxa de proteína inferior a 12,4 g/kg.


## Exercícios

2. Foi contado o número de crianças não-vacinadas em cada uma das 50 famílias escolhidas aleatoriamente no
Bairro Pinheirinhos em Alfenas, encontrando-se o seguinte resultado:

| 5 | 1 | 5 | 3 | 1 | 2 | 2 | 1 | 1 | 0 |
| 4 | 2 | 0 | 4 | 4 |
4 | 4 | 3 | 3 | 2 |
| 1 | 1 | 3 | 2 | 3 | 1 | 2 | 3 | 4 | 3 |
| 4 | 0 | 2 | 0 | 5 | 2 | 3 | 4 | 3 | 4 |
| 0 | 0 | 4 | 3 | 2 | 2 | 4 | 3 | 4 | 3 |

a) Calcule a média, mediana e moda.

## Respostas

2. a) Média = 2,4; Mediana = 2,5; Moda = 3

## Exercícios

3. Um laboratório que fabrica comprimidos analgésicos anuncia que seu remédio contra dor de cabeça tem a
mesma média e uma variação menor na quantidade do princípio ativo em relação ao analgésico tradicional.
Avaliaram se 8 amostras aleatórias de cada analgésico, obtendo-se os seguintes resultados (em mg)

|           | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 |
|-----------|---|---|---|---|---|---|---|---|---|
| Novo      | 6 | 5 | 8 | 5 | 6 | 7 | 6 | 6 |   |
| Tradicional | 8 | 6 | 5 | 7 | 4 | 9 | 5 | 6 |   |

Pode-se afirmar que o fabricante tem razão? Calcule a medidas de interesse e conclua.

## Respostas

3. Média Novo = 6,1; Média Tradicional = 6,1; Variância Novo = 0,7; Variância Tradicional = 2,1; Desvio Padrão Novo = 0,8; Desvio Padrão Tradicional = 1,4; Coeficiente de Variação Novo = 0,13; Coeficiente de Variação Tradicional = 0,23; Erro Padrão da Média Novo = 0,3; Erro Padrão da Média Tradicional = 0,5; Como o desvio padrão do novo é menor que o desvio padrão do tradicional, o fabricante tem razão.

## Exercícios

4. Para estudar o rendimento de proteína de certo cultivar de aveia branca um pesquisador coletou 12 amostras,
cujo rendimento de proteína foi medido. Os resultados obtidos, (em mg/g), foram os seguintes:

| 148 |116| 126| 148| 135 |144| 129|128| 120| 146| 140| 146|

a)  Determine a média, a mediana, a moda, e o Q1 e Q3 do rendimento de proteína.

b) Qual é a medida de posição mais apropriada para representar esse conjunto de dados? Justifique.

c) Você acha que a variabilidade dos dados é grande ou pequena? Por quê?

## Respostas

4. a) Média = 134,5; Mediana = 137,5; Moda = 146; Q1 = 126; Q3 = 146

   b) Mediana, pois a distribuição é assimétrica.

   c) Grande, pois o desvio padrão é 11,5.

## Exercícios

5. Examinou-se um lote de 100 caixas de um fármaco, escolhidas aleatoriamente num carregamento de 10000
caixas prontas para exportação, anotando o número de "vidros"com pH maior que o permitido (fora do
padrão) por caixa (cada caixa contem 20 vidros). Os resultados foram os seguintes:

| Número de vidros fora do padrão | 0 | 1 | 2 | 3 | 4 | 5 |
|--------------------------------|---|---|---|---|---|---|
| Número de caixas (frequência)   | 40 | 28 | 12 | 10 | 6 | 4 |


a) Qual é o número médio, mediano e modal, de vidros "Fora do Padrão"por caixa?

b) Qual deverá ser o número total de vidros "fora do padrão"no carregamento?

## Respostas

5. a) Média = 1,2; Mediana = 1; Moda = 0

   b) 1200

## Exercícios

Um medicamento utilizado em enfermidades decorrentes de contraturas musculares dolorosas contém em
sua formulação a cafeína que é um estimulante do sistema nervoso central que atua sobre a musculatura
estriada tornando-a menos susceptível à fadiga. Um pesquisador com o intuito de verificar a quantidade
de cafeína (em mg) num "medicamento A? analisou uma amostra aleatória de 12 comprimidos obtendo os
seguintes resultados:


3 |4 |5| 4| 3| 6| 3| 4| 2 |4 |4| 3|

a) Calcule a média, mediana, moda, o terceiro quartil (Q3), o erro padrão e o coeficiente de variação.

## Respostas

6. a) Média = 3,75; Mediana = 3,5; Moda = 4; Q3 = 4; Erro Padrão = 0,3; Coeficiente de Variação = 0,2

## Exercícios

7. Considere os conjuntos de dados da quantidade de um determinado exame realizado em dois laboratórios:


| Laboratório       | 380 | 360 | 370 | 1000 | 320 | Non|| Non|
|-------------------|-----|-----|-----|------|-----|-----|-----|-----|
| Laboratório A     | 380 | 360 | 370 | 1000 | 320 | 
| Laboratório B     | 720 | 750 | 740 | 730  | 760 | 720 | 770 |


Calcule (somente) a medida de posição mais apropriada para cada conjunto de dados. Comente o porque.

## Respostas

7. Laboratório A: Mediana, pois a distribuição é assimétrica.

   Laboratório B: Média, pois a distribuição é simétrica.

## Exercícios

8. Considere os conjuntos de dados a seguir referentes aos preços (em reais) de um remédio em diferentes
farmácias de cidades.

|          | 58 | 56 | 57 | 60 | 62 | 62 | 77 |
|----------|----|----|----|----|----|----|----|
| Cidade A | 58 | 56 | 57 | 60 | 62 | 62 |    |
| Cidade B | 72 | 75 | 74 | 73 | 74 | 72 | 77 |
| Cidade C | 48 | 49 | 45 | 47 | 43 |    |    |


Qual é a cidade com maior variabilidade nos preços?

## Respostas

8. Cidade A: Desvio Padrão = 2,1

   Cidade B: Desvio Padrão = 1,2

   Cidade C: Desvio Padrão = 2,1

   Cidade A e C possuem a mesma variabilidade.

## Exercícios


9. Para verificar o número de lesões musculares que os atletas de um clube já sofreram foram entrevistados
aleatoriamente 50 atletas obtendo os seguintes resultados:

| Número de lesões (xi) | 0 | 1 | 2 | 3 | 4 | 5 |
|-----------------------|---|---|---|---|---|---|
| Frequência de atletas | 14 | 20 | 9 | 4 | 2 | 1 |


a) Calcule a média, mediana, moda e o coeficiente de variação do número de lesões musculares por atleta.

## Respostas

9. a) Média = 1,1; Mediana = 1; Moda = 1; Coeficiente de Variação = 0,9
