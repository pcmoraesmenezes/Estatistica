# PROBABILIDADE

## Introdução

O que é o processo de inferência? É o processo de tirar conclusões sobre uma população a partir de uma amostra.

A maior parte dos resultados obtidos em sociedade está associado ao processo de amostragem.

**Inferência** Estatistica é o processo de tirar conclusões sobre uma população a partir de uma amostra. Ou seja não se tem conhecimento total da população, mas se tem conhecimento de uma parte dela.

Estimativa nada mais é do que o valor aproximado calculado a partir de uma amostra, com um parametro desconhecido.

A probabilidade é uma teória que surge com o intuito de calcular as incertezas de um processo de inferência. Como por exemplo, a probabilidade de um evento ocorrer.

### Contextos importantes:

Existem modelos chamados de modelos deterministicos, esses modelos, são modelos que não possuem incertezas, ou seja, o resultado é sempre o mesmo. Por exemplo, o lançamento de uma moeda, o resultado é sempre cara ou coroa.

Entretanto se um fenomeno não está fixado em alguma lei ou se as leis são desconhecidas, nada pode ser afirmado a principio sobre o resultado de um experimento. Por exemplo, o lançamento de um dado, não se sabe qual será o resultado, pois não se sabe qual a força que será aplicada, qual a posição inicial, qual a posição final, etc.

Quando não se tem a certeza sobre o resultado de um estudo, chamamos de modelo probabilistico.

### Algumas probabilidades básicas:

- **Se jogar uma moeda para o alto, qual a probabilidade de dar cara?** 50%

- **Se jogar um dado para o alto, qual a probabilidade de dar 6?** 16,66%

- **Se uma mulher está grávida, qual a probabilidade de ter um menino?** 50%

Entretanto, é importante observar que existem situações em que a probabilidade não é tão simples de ser calculada, por exemplo:

- **Se uma pessoa está com febre, qual a probabilidade de ter dengue?**

- **Se uma pessoa está com febre, qual a probabilidade de ter covid?**

- **Se uma pessoa está com febre, qual a probabilidade de ter gripe?**


### Definições:

#### Experimento aleatório:

Fenomenos produzidos pelo homem cujo resultado é imprevisivel.

- Lançamento de um dado

- Tempo de duração de uma bateria

Mesmo que os resultados iniciais sejam os mesmos, o resultado final pode ser diferente.

#### Experimento deterministico

O oposto do experimento aleatório, ou seja, o resultado é previsivel.

- Temperatura de solidificação da água

#### Probabilidade Priori:

Quando se pode ter conhecimento do resultado de um experimento antes de sua realização.

#### Probabilidade Posteriori:

Quando se pode ter conhecimento do resultado de um experimento após a sua realização.

#### Probabilidade Baysiana:

Quando se pode ter conhecimento do resultado de um experimento antes e após a sua realização.

#### Espaços amostrais:

Representado pela letra grega Ω (Omega), ou S, é o conjunto de todos os resultados possiveis de um experimento aleatório.

Exemplos:

Ω1 = {1,2,3,4,5,6}

Ω2 = {CC, FC, FF, CF} = {(C,C), (F,C), (F,F), (C,F)}

Ω3 = Conjunto dos numeros reais

Ω4 = Conjunto dos numeros inteiros

#### Evento

Eventos são subconjuntos do espaço amostral.

Denotado por letras maiusculas, por exemplo, A, B, C, etc.


#### Probabilidade de um evento

A probabilidade de um evento é a razão entre o número de casos favoráveis e o número de casos possiveis.

P(E) = n(E) / n(Ω) 

- Em que P(E) é a probabilidade do evento E

- n(E) é o número de casos favoráveis

- n(Ω) é o número de casos possiveis

Exemplos:

- Lançamento de um dado, qual a probabilidade de dar 6?

Ω = {1,2,3,4,5,6}

E = {6}

P(E) = 1/6

- Lançamento de uma moeda, qual a probabilidade de dar cara?

Ω = {C, F}

E = {C}

P(E) = 1/2

#### Axiomas da probabilidade

- A probabilidade de um evento é sempre um número entre 0 e 1

0 <= P(E) <= 1

P(Ω) = 1 e P(Ø) = 0, ou seja a probabilidade do espaço amostral é 1 e a probabilidade do conjunto vazio é 0.

- Se A e B são eventos mutuamente exclusivos, então a probabilidade de A ou B é a soma das probabilidades de A e B.

P(A U B) = P(A) + P(B)

- Se A e B são eventos quaisquer, então a probabilidade de A ou B é a soma das probabilidades de A e B menos a probabilidade de A e B.

P(A U B) = P(A) + P(B) - P(A ∩ B)

- Se A e B são eventos quaisquer, então a probabilidade de A e B é a probabilidade de A vezes a probabilidade de B.

P(A ∩ B) = P(A) * P(B)

#### Probabilidade condicional
Dados dois eventos A e B, representada por P(A|B), é a probabilidade de A ocorrer dado que B ocorreu.

P(A|B) = P(A ∩ B) / P(B), se P(B) > 0

Diz-se que dois eventos são independentes se a ocorrência de um não afeta a ocorrência do outro.

P(A|B) = P(A) e P(B|A) = P(B)

Exemplo

| Resposta      | Novo | Tradicional | Total |
|---------------|-----:|------------:|------:|
| Falhou        |   10 |          20 |    30 |
| Não falhou    |   30 |          40 |    70 |
| **Total**     |   40 |          60 |   100 |

Seu chip é escolhido ao acaso:

I) Qual a probabilidade de falhar dado que foi produzido pelo novo processo?

P(F|N) = 10/40 = 0,25

II) Qual a probabilidade de falhar dado que foi produzido pelo processo tradicional?

P(F|T) = 20/60 = 0,33

III) Qual a probabilidade de falhar?

P(F) = 30/100 = 0,3

IV) Qual a probabilidade de ter sido produzido pelo novo processo dado que falhou?

P(N|F) = P(N ∩ F) / P(F) = 10/30 = 0,33

V) Qual a probabilidade de ter sido produzido pelo processo tradicional dado que falhou?

P(T|F) = P(T ∩ F) / P(F) = 20/30 = 0,66

VI) Novo processo tem efitividade? (P(N|F) > P(N))

P(N|F) = 0,33

P(N) = 0,4

P(N|F) > P(N) = 0,33 > 0,4

## Exercicios:

1) A probabilidade de um homem esteja vivo daqui 30 anos é 2/5 e a de sua mulher é 2/3. Determine a probabilidade daqui a 30 anos:

a) Ambos estarem vivos

b) Apenas um deles estar vivo

c) Nenhum deles estar vivo

d) Apenas o homem estar vivo

e) Apenas a mulher estar viva

2. Uma companhia de seguros analisou a frequência com que 2.000 segurados (1.000 homens e 1.000
mulheres) usaram o hospital. Os resultados são apresentados na tabela:

| Resposta       | Homens | Mulheres |
|----------------|-------:|--------:|
| Usaram         |    120 |     200 |
| Não usaram     |    880 |     800 |


(a) Qual a probabilidade de que uma pessoa segurada use o hospital?

(b) Qual a probabilidade de ser mulher dado que usou o hospital?

(c) Qual a probabilidade de ser homem dado que usou o hospital?

(d) O uso do hospital independe do sexo do segurado?


3. Em uma estufa, o pesquisador verifica que existem plantas doentes ou resistentes. Para amostras de 3
plantas selecionadas ao acaso. Escreva o espaço amostral e determine qual é a probabilidade que:

a) Mais de uma planta seja resistente.

b) No máximo duas plantas sejam resistentes.

c) Nenhuma planta resistente.

d) Suponha que a probabilidade que uma planta seja resistente a uma determinada doença é 75%.

d1) Mais de uma planta seja resistente.

d2) No máximo duas plantas sejam resistentes.

4. O responsável pelo restaurante de uma empresa suspeitou que o feijão que estava armazenado poderia
estar contaminado com fungos, e realizou um experimento. Ele pegou aleatoriamente uma amostra de 5
saquinhos do produto e observou a presença ou não de fungos.

i) Determine (escreva) o espaço amostral.

ii) Qual a probabilidade de termos os eventos:

a) E1: Ter exatamente 2 saquinhos contaminados.

b) E2: Ter 2 ou mais saquinhos não contaminados.

c) E3: Ter pelo menos um saquinho não contaminado.

d) E4: Ter a primeiro ou o segundo saquinho contaminado

e) Considerando que a probabilidade de um saquinho estar contaminado seja de 0,30. Qual a probabilidade de termos:

e1) Exatamente 2 saquinhos Contaminados.

e2) Exatamente 1 saquinho Não Contaminado.

5. A probabilidade de que um médico faça o diagnóstico correto de uma doença é de 0,7. Dado que o
médico fez um diagnóstico incorreto, a probabilidade de que o paciente entre com um processo é de 0,9.
Qual é a probabilidade de que o médico erre o diagnóstico e seja processado pelo paciente?

6. De um total de 500 empregados, 200 possuem plano pessoal de aposentadoria complementar, 400 contam
com o plano de aposentadoria complementar oferecido pela empresa e 200 empregados possuem ambos
os planos. Sorteia-se aleatoriamente um empregado dessa empresa.

a) Qual é a probabilidade de que ele tenha algum plano de aposentadoria complementar?

b) Qual é a probabilidade de que ele não possua qualquer plano de aposentadoria complementar?

c) Se o empregado conta com o plano de aposentadoria complementar oferecido pela empresa, qual é a
probabilidade de que ele tenha plano pessoal de aposentadoria complementar?

d) Se o empregado tem plano pessoal de aposentadoria complementar, qual é a probabilidade de que ele
conte com o plano de aposentadoria complementar da empresa?

## Respota dos exercicios:

1) A probabilidade de um homem esteja vivo daqui 30 anos é 2/5 e a de sua mulher é 2/3. Determine a probabilidade daqui a 30 anos:

a) Ambos estarem vivos

P(A ∩ B) = P(A) * P(B) = 2/5 * 2/3 = 4/15

b) Apenas um deles estar vivo

P(A ∩ B') + P(A' ∩ B) = P(A) * P(B') + P(A') * P(B) = 2/5 * 1/3 + 3/5 * 2/3 = 2/15 + 6/15 = 8/15

c) Nenhum deles estar vivo

P(A' ∩ B') = P(A') * P(B') = 3/5 * 1/3 = 3/15 = 1/5

d) Apenas o homem estar vivo

P(A ∩ B') = P(A) * P(B') = 2/5 * 1/3 = 2/15

e) Apenas a mulher estar viva

P(A' ∩ B) = P(A') * P(B) = 3/5 * 2/3 = 6/15 = 2/5

2. Uma companhia de seguros analisou a frequência com que 2.000 segurados (1.000 homens e 1.000

mulheres) usaram o hospital. Os resultados são apresentados na tabela:

| Resposta       | Homens | Mulheres |
|----------------|-------:|--------:|
| Usaram         |    120 |     200 |
| Não usaram     |    880 |     800 |


(a) Qual a probabilidade de que uma pessoa segurada use o hospital?

P(U) = P(U ∩ H) + P(U ∩ M) = 120/2000 + 200/2000 = 320/2000 = 0,16

(b) Qual a probabilidade de ser mulher dado que usou o hospital?

P(M|U) = P(M ∩ U) / P(U) = 200/320 = 0,625

(c) Qual a probabilidade de ser homem dado que usou o hospital?

P(H|U) = P(H ∩ U) / P(U) = 120/320 = 0,375

(d) O uso do hospital independe do sexo do segurado?

P(H ∩ U) = P(H) * P(U) = 1000/2000 * 320/2000 = 320/4000 = 0,08

P(M ∩ U) = P(M) * P(U) = 1000/2000 * 320/2000 = 320/4000 = 0,08

3. Em uma estufa, o pesquisador verifica que existem plantas doentes ou resistentes. Para amostras de 3

plantas selecionadas ao acaso. Escreva o espaço amostral e determine qual é a probabilidade que:

a) Mais de uma planta seja resistente.

Ω = {DDD, DDR, DRD, RDD, RRD, RDR, DRR, RRR}

P(R) = 7/8

b) No máximo duas plantas sejam resistentes.

P(R) = 7/8

c) Nenhuma planta resistente.

P(R') = 1/8

d) Suponha que a probabilidade que uma planta seja resistente a uma determinada doença é 75%.

d1) Mais de uma planta seja resistente.

P(R) = 0,75

d2) No máximo duas plantas sejam resistentes.

P(R) = 0,75

4. O responsável pelo restaurante de uma empresa suspeitou que o feijão que estava armazenado poderia

estar contaminado com fungos, e realizou um experimento. Ele pegou aleatoriamente uma amostra de 5

saquinhos do produto e observou a presença ou não de fungos.

i) Determine (escreva) o espaço amostral.

Ω = {CCCCC, CCCCF, CCCFF, CCFFF, CFFFF, FFFFF, FFFFC, FFFCC, FFCCC, FCCCC}

ii) Qual a probabilidade de termos os eventos:

a) E1: Ter exatamente 2 saquinhos contaminados.

P(E1) = 10/10 = 1

b) E2: Ter 2 ou mais saquinhos não contaminados.

P(E2) = 10/10 = 1

c) E3: Ter pelo menos um saquinho não contaminado.

P(E3) = 10/10 = 1

d) E4: Ter a primeiro ou o segundo saquinho contaminado

P(E4) = 10/10 = 1

e) Considerando que a probabilidade de um saquinho estar contaminado seja de 0,30. Qual a probabilidade de termos:

e1) Exatamente 2 saquinhos Contaminados.

P(E1) = 0,3 * 0,3 = 0,09

e2) Exatamente 1 saquinho Não Contaminado.

P(E2) = 0,7 * 0,7 = 0,49

5. A probabilidade de que um médico faça o diagnóstico correto de uma doença é de 0,7. Dado que o

médico fez um diagnóstico incorreto, a probabilidade de que o paciente entre com um processo é de 0,9.

Qual é a probabilidade de que o médico erre o diagnóstico e seja processado pelo paciente?

P(E) = P(E ∩ F) + P(E ∩ F') = P(E|F) * P(F) + P(E|F') * P(F') = 0,3 * 0,9 + 0,7 * 0,1 = 0,27 + 0,07 = 0,34

6. De um total de 500 empregados, 200 possuem plano pessoal de aposentadoria complementar, 400 contam

com o plano de aposentadoria complementar oferecido pela empresa e 200 empregados possuem ambos

os planos. Sorteia-se aleatoriamente um empregado dessa empresa.

a) Qual é a probabilidade de que ele tenha algum plano de aposentadoria complementar?

P(A) = P(A ∩ B) + P(A ∩ B') = P(A|B) * P(B) + P(A|B') * P(B') = 200/500 + 200/500 = 400/500 = 0,8

b) Qual é a probabilidade de que ele não possua qualquer plano de aposentadoria complementar?

P(A') = 1 - P(A) = 1 - 0,8 = 0,2

c) Se o empregado conta com o plano de aposentadoria complementar oferecido pela empresa, qual é a

probabilidade de que ele tenha plano pessoal de aposentadoria complementar?

P(A|B) = P(A ∩ B) / P(B) = 200/400 = 0,5

d) Se o empregado tem plano pessoal de aposentadoria complementar, qual é a probabilidade de que ele

conte com o plano de aposentadoria complementar da empresa?

P(B|A) = P(B ∩ A) / P(A) = 200/200 = 1

## Variavel aleatoria

Uma variavel aleatoria é uma função que associa a cada elemento do espaço amostral um número real.

Uma quantidade X, associada a cada resultado possível do espaço amostral, é denominado variavel aleatoria discreta, se X assumir uma quantidade enumeravel de valores. Por exemplo, o número de caras em 3 lançamentos de uma moeda. Por outro lado uma variavel aleatoria é denominada variavel aleatoria continua se X assumir uma quantidade não enumeravel de valores. Por exemplo, o tempo de vida de uma bateria.

Exemplo:

Observar o estado de 3 equipamentos de um laboratório e determinar sua condição (DEFEITO -
D ou BOM - B)

Ω = {DDD, DDB, DBD, DBB, BDD, BDB, BBD, BBB}

EVENTOS:

- Ter exatamente 2 equipamentos em bom estado:
    E1 = {DBB, BDB, BBD}

- Ter 2 ou mais equipamentos em bom estado:
    E2 = {DBB, BDB, BBD, BBB}

- Complemento de 3 defeituosos:
    E3 = {DDD}

X = numero de equipamentos em bom estado {0, 1, 2, 3}.

P(E1) = P(X=2)

P(E2) = P(X>=2)

Variaveis aleatorias usualmente são denotadas por letras maiusculas, por exemplo, X, Y, Z, etc.

### Distribuição de probabilidade

É uma tabela que relaciona os valores assumidos pela variavel aleatoria X com suas respectivas probabilidades.

$f:X \rightarrow P(X=x)$ 

Exemplo:

| X | P(X=x) |
|---|--------|
| 0 | 0,125  |
| 1 | 0,375  |
| 2 | 0,375  |
| 3 | 0,125  |

## Distribuição Binomial

Frequentemente usada para descrever situações em que a variavel de uma população em estudo tem duas respostas possíveis (sucesso ou fracasso). Constituem do processo de Bernoulli.

### Processo de Bernoulli

É um processo aleatório que consiste em n ensaios independentes, cada um deles com dois resultados possíveis, sucesso ou fracasso.

Cada experimento é dito ser uma tentativa. O resultado de cada tentativa é chamado de resultado do experimento.

A probabilidade de sucesso é igual a p e a probabilidade de fracasso é igual a q = 1 - p.

Os resultados são estatisticamente independentes.

Quando um experimento aleatório com apenas 2 resultados possíveis (sucesso ou fracasso) é repetido
"n"vezes, a variável aleatória discreta definida como:
X: número de sucessos ocorridos em "n"tentativas (ou experimentos).
Tem uma distribuição da forma:

$f(x) = \binom{n}{x} p^x (1-p)^{n-x}$

Onde:

- n é o número de tentativas (ou experimentos)

- x é o número de sucessos

- p é a probabilidade de sucesso

- q é a probabilidade de fracasso

- p + q = 1

- $ \binom{n}{x} = \frac{n!}{x!(n-x)!}$


Exemplo:

 Sabe-se que a probabilidade de eficiência da vacina anti-gripal para idosos é de 80%. Num grupo
de 10 idosos imunizados com a vacina anti-gripal, determine a probabilidade dos eventos:

- De que exatamente 6 idosos imunizados não tenham gripe.

- De que no máximo 5 idosos imunizados não tenham gripe

- De que mais de 7 idosos imunizados não tenham gripe.

Importante:

Identificar a variavel aleatoria, sua distribuição com respectivos parametros.

Escrever a questão na notação de probabilidade

X: número de idosos que não contraíram gripe no grupo de 10 idosos imunizados com a vacina anti-gripal.

A aplicação da vacina em
cada idoso pode ser considerado como um ensaio que pode produzir apenas dois resultados: o idoso ter gripe
ou o idoso não ter gripe. O fato de um idoso imunizado ter ou não gripe não interfere na chance de outro idoso
imunizado contrair ou não a gripe, ou seja, o ensaios são independentes.

Trata-se de uma distribuição binomial com n = 10, p = 0,8 e q = 0,2.

Onde n é o número de tentativas (ou experimentos), p é a probabilidade de sucesso e q é a probabilidade de fracasso.

$X \sim B(10; 0,8)$

Item a:

P(X=6) = $\binom{10}{6} 0,8^6 (1-0,8)^{10-6}$ = 0,0881

Item b:

P(X<=5) = 0,0328

Item c:

P(X>7) = 0,6778

## Distribuição de Poisson

É uma distribuição de probabilidade discreta que expressa a probabilidade de uma série de eventos ocorrer num certo período de tempo se estes eventos ocorrem com uma taxa média conhecida e independente do tempo desde o último evento.

A função X é uma variavel aleatoria discreta que assume valores inteiros não negativos. Tem-se a seguinte forma:

$f(x) = \frac{e^{-\lambda} \lambda^x}{x!}$

Onde:

- $\lambda$ é o número médio de eventos ocorrendo num intervalo de tempo especificado

- x é o número de eventos ocorrendo num intervalo de tempo especificado

- e é o número de Euler

Exemplo: Sabe-se que o número médio de interrupções do serviço de internet a cada mês (4 semanas) é de
10 interrupções, qual é a probabilidade de que:

- Em uma semana ocorra, exatamente, 1 interrupção do serviço de internet ?

- Em uma semana ocorram, no máximo, 2 interrupções do serviço de internet?

- Em uma semana ocorram mais de 2 interrupções do serviço de internet?

A variavel aleatoria X é o número de interrupções do serviço de internet em uma semana.

$X \sim Poisson(\lambda)$

O valor de $\lambda$ é o numero medio de interrupções do serviço de internet a cada mês (4 semanas) é de 10 interrupções.

$\lambda = 10/4 = 2,5$

Item a:

P(X=1) = $\frac{e^{-2,5} 2,5^1}{1!}$ = 0,2052

Item b:

P(X<=2) = 0,5438

Item c:

P(X>2) = 0,4562


## Exercicios:

Para todos os exercícios, identificar a variável aleatória, sua distribuição com respectivos parâmetros e escrever a questão na notação de probabilidade

 Um laboratório químico encomendou uma remessa de 400 pHmetros. O fabricante sabe que 40 pHmetros enviados estão defeituosos. O laboratório inspecionará de 20 pHmetros escolhidos aleatoriamente e somente aceitará a remessa se ocorrer no máximo um pHmetro defeituoso. Qual a probabilidade de:

a) A remessa ser aceita?

b) Ter nenhum defeituoso?

c) Ter mais de 5 defeituosos?

X: número de pHmetros defeituosos em uma amostra de 20 pHmetros.

$X \sim B(20; 0,1)$

0,1 é a probabilidade de um pHmetro ser defeituoso.

a) P(X<=1) = 0,9887

b) P(X=0) = 0,1216

c) P(X>5) = 0,0000


Uma remessa de 800 estabilizadores de tensão é recebida pelo controle de qualidade de uma empresa. São inspecionados 20 aparelhos da remessa, que será aceita se ocorrer no máximo um defeituoso. Há 80 defeituosos no lote. Qual a probabilidade do lote ser aceito?

X: número de estabilizadores defeituosos em uma amostra de 20 estabilizadores.

$X \sim B(20; 0,1)$

0,1 é a probabilidade de um estabilizador ser defeituoso.

P(X<=1) = 0,9887

. Em momentos de pico chegam, em média, 1 avião por minuto em um determinado aeroporto.

(a) Determine a probabilidade de 3 chegadas em um minuto qualquer do horário de pico.

(b) Determine a probabilidade de que nenhum avião chegue nesse aeroporto no horário de pico.

(c) Se o aeroporto pode atender 2 aviões por minuto, qual a probabilidade de haver aviões sem atendimento imediato?

X: número de aviões que chegam em um minuto qualquer do horário de pico.

$X \sim Poisson(1)$

1 é o número médio de aviões que chegam em um minuto qualquer do horário de pico.

(a) P(X=3) = 0,0613

(b) P(X=0) = 0,3679

(c) P(X>2) = 0,3233

Sabe-se que 60% dos camundongos inoculados com soro estão protegidos contra determinada doença. Se cinco camundongos são inoculados, determine a probabilidade de que:

X: número de camundongos protegidos contra determinada doença.

$X \sim B(5; 0,6)$

0,6 é a probabilidade de um camundongo estar protegido contra determinada doença.

(a) P(X=0) = 0,0102

(b) P(X<2) = 0,0784

(c) P(X>3) = 0,3456

(d) P(X>=4) = 0,2304


Uma certa doença pode ser curada através de procedimento cirúrgico em 80% dos casos. Dentre os que têm essa doença, sorteamos 15 paciente que serão submetidos à cirurgia. Fazendo alguma suposição adicional que julgar necessária, responda qual é a probabilidade de:

X: número de pacientes curados dentre os 15 que serão submetidos à cirurgia.

$X \sim B(15; 0,8)$

0,8 é a probabilidade de um paciente ser curado.

(a) P(X=15) = 0,0352

(b) P(X>=2) = 0,9999

(c) P(X>=10) = 0,9999

A aplicação de fundo anticorrosivo em chapas de aço é feita mecanicamente e pode produzir, em média, 3 defeitos por m2 . Uma chapa de 4 m2 é sorteada ao acaso para ser inspecionada. Qual é a probabilidade:

X: número de defeitos em uma chapa de 4 m2.

$X \sim Poisson(12)$

12 é o número médio de defeitos em uma chapa de 4 m2.

(a) P(X>=1) = 0,9999

(b) P(X>=3) = 0,9999

(c) P(X<=6) = 0,9999

(d) P(2<=X<=6) = 0,9999

(e) P(X<=1) = 0,9999

Uma indústria de seringas garante que em 95% dos pedidos atendidos, os clientes ficam plenamente satisfeitos com o prazo de entrega e com a qualidade do produto. Uma drogaria fez 10 pedidos a essa indústria.

(a) Qual a probabilidade de que fique plenamente satisfeito nos dez pedidos?

(b) Qual a probabilidade de que fique plenamente satisfeito em oito pedidos?

(c) Qual a probabilidade de que fique plenamente satisfeito, no mínimo, em seis pedidos?

(d) Qual a probabilidade de que fique plenamente satisfeito, no mínimo, em oito pedidos?

X: número de pedidos em que os clientes ficam plenamente satisfeitos com o prazo de entrega e com a qualidade do produto.

$X \sim B(10; 0,95)$

0,95 é a probabilidade de um pedido ser plenamente satisfeito com o prazo de entrega e com a qualidade do produto.

(a) P(X=10) = 0,5987

(b) P(X=8) = 0,0000

(c) P(X>=6) = 0,9999

(d) P(X>=8) = 0,0000

Numa cidade ouviu-se a opinião de 60 adultos sobre um projeto de lei proposto pela prefeitura. Os adultos pesquisados só poderiam responder "a favor"ou "contra". Como resultado, observou-se que 40 dos adultos pesquisados foram a favor do projeto. Se na realidade as opiniões pró e contra são igualmente divididas, qual é a probabilidade de ter obtido tal resultado?

X: número de adultos que foram a favor do projeto.

$X \sim B(60; 0,5)$

0,5 é a probabilidade de um adulto ser a favor do projeto.

P(X=40) = 0,0000

Sabe-se que 20% dos animais submetidos a um certo tratamento não sobrevivem. Se esse tratamento foi aplicado em 20 animais e se X é o número de não sobreviventes:

(a) Qual é a distribuição de X?

(b) Calcule P(X = 0)

(c) Calcule P(2 < X ≤ 4)

(d) Calcule P(X ≥ 2)

X: número de animais que não sobreviveram.

$X \sim B(20; 0,2)$

0,2 é a probabilidade de um animal não sobreviver.

(b) P(X=0) = 0,0000

(c) P(2 < X ≤ 4) = 0,0000

(d) P(X >= 2) = 0,0000

O número de partículas gama emitidas por segundo, por uma certa substância radioativa, é uma variável aleatória com distribuição de Poisson com λ = 0, 3. Se o instrumento registrador torna-se inoperante quando há mais de 4 partículas por segundo, qual a probabilidade de isso ocorrer em qualquer dado segundo?

X: número de partículas gama emitidas por segundo.

$X \sim Poisson(0,3)$

0,3 é o número médio de partículas gama emitidas por segundo.

P(X>4) = 0,0000

## Distribuição de probabilidade continua

Associada a uma variavel aleatoria continua X, existe uma função f(x) chamada de função densidade de probabilidade (fdp) ou função densidade de frequência (fdf), que satisfaz as seguintes condições:

- f(x) >= 0 para todo x

- $\int_{-\infty}^{\infty} f(x) dx = 1$

- P(a <= X <= b) = $\int_{a}^{b} f(x) dx$

### Distribuição normal ou gaussiana

É a mais importante distribuição de variáveis aleatórias contínuas, devido à sua enorme aplicação nos mais
variados campos do conhecimento.
"Qualquer que seja a variável aleatória em estudo, é necessário reconhecer primeiro, qual é a função de
densidade de probabilidades (fdp) associada a ela."

A função de densidade de probabilidades (fdp) de uma variável aleatória contínua X é dada por:

$f(x) = \frac{1}{\sigma \sqrt{2\pi}} e^{-\frac{(x-\mu)^2}{2\sigma^2}}$

Onde:

- $\mu$ é a média da variável aleatória X

- $\sigma$ é o desvio padrão da variável aleatória X

- $\sigma^2$ é a variância da variável aleatória X

- $\pi$ é o número de Euler

- e é o número de Euler

- $-\infty < x < \infty$

- $-\infty < \mu < \infty$

Calculando a probabilidade de um intervalo com distribuição normal:

Sabe-se que o tempo de duração de uma certa bateria (Marca WW) têm uma distribuição Normal com
média 200 horas e desvio padrão 20 horas. Qual a probabilidade de que uma bateria escolhida ao acaso desta
população tenha:

a) um tempo de duração inferior a 225h.

b) um tempo de duração superior a 225h.

c) tempo de duração entre 200h e 225h .

X: tempo de duração de uma certa bateria (Marca WW) têm uma distribuição Normal com média 200 horas e desvio padrão 20 horas.

USANDO O SOFTWARE R + RCMDR:

ETAPAS:

1. DISTRIBUIÇÃO CONTINUA

2. DISTRIBUIÇÃO NORMAL

3. PROBABILIDADE DA NORMAL

A) 0.89

B) 0.11

C) 0.39

LISTA DE EXERCICIOS DE PROBABILIDADE

Escreva com suas palavras o que você entende por:

a) Experimento Aleatório

- É um experimento que pode ser repetido em condições similares, mas que não se pode prever o resultado. Por exemplo, lançar um dado.

b) Espaço Amostral

- É o conjunto de todos os resultados possíveis de um experimento aleatório. Por exemplo, lançar um dado, o espaço amostral é {1,2,3,4,5,6}.

c) Evento

- É um subconjunto do espaço amostral. Por exemplo, lançar um dado, o evento A = {2,4,6}.

d) Complementar de um evento

- É o conjunto de todos os resultados possíveis que não pertencem ao evento. Por exemplo, lançar um dado, o evento A = {2,4,6}, o complementar de A é A' = {1,3,5}.

e) União de dois eventos

- É o conjunto de todos os resultados possíveis que pertencem a pelo menos um dos eventos. Por exemplo, lançar um dado, o evento A = {2,4,6} e o evento B = {1,2,3}, a união de A e B é A U B = {1,2,3,4,6}.

f) Interseção de dois eventos

- É o conjunto de todos os resultados possíveis que pertencem a ambos os eventos. Por exemplo, lançar um dado, o evento A = {2,4,6} e o evento B = {1,2,3}, a interseção de A e B é A ∩ B = {2}.

g) Eventos mutuamente exclusivos

---

- São eventos que não podem ocorrer ao mesmo tempo. Por exemplo, lançar um dado, o evento A = {2,4,6} e o evento B = {1,3,5}, são mutuamente exclusivos.

Escreva um espaço amostral para cada experimento abaixo:

a) Uma letra é escolhida entre as letras da palavra PROBABILIDADE

- Ω = {P, R, O, B, A, I, D, L, E}

b) Uma urna contém bolas vermelhas (V), bolas brancas (B) e bolas azuis (A). Uma bola é extraída e observada pela sua cor

- Ω = {V, B, A}

c) Uma moeda é lançada 3 vezes e observado o número de caras

- Ω = {CCC, CCF, CFC, FCC, FCC, FCF, FFC, FFF}

d) De um baralho de 52 cartas, uma e extraida e observada

- Ω = {A♠, 2♠, 3♠, 4♠, 5♠, 6♠, 7♠, 8♠, 9♠, 10♠, J♠, Q♠, K♠, A♥, 2♥, 3♥, 4♥, 5♥, 6♥, 7♥, 8♥, 9♥, 10♥, J♥, Q♥, K♥, A♦, 2♦, 3♦, 4♦, 5♦, 6♦, 7♦, 8♦, 9♦, 10♦, J♦, Q♦, K♦, A♣, 2♣, 3♣, 4♣, 5♣, 6♣, 7♣, 8♣, 9♣, 10♣, J♣, Q♣, K♣}

e_ um casal planeja ter 3 filhos. O sexo de cada criança é observado

- Ω = {MMM, MMF, MFM, FMM, FFM, FMF, MFF, FFF} EM que M representa menino e F representa menina.

---

Uma urna contém 30 bolas enumeradas de 1 a 30. Uma bola é escolhida e observado o seu número. Seja Ω = {1,2,3,..30} Descreva os eventos:

a) O numero obtido é par

- A = {2,4,6,8,...28,30}

b) O numero obtido é impar

- B = {1,3,5,7,...27,29}

c) O numero obtido é primo

- C = {2,3,5,7,11,13,17,19,23,29}

d) O numero obtido é maior que 16

- D = {17,18,19,20,21,22,23,24,25,26,27,28,29,30}

e) O numero obtido é multiplo de 2 e 5

- E = {10,20,30}

f) o numero obtido é multiplo de 3 ou de 8

- F = {3,6,8,9,12,15,18,21,24,27,30}

g) o numero obtido não é multiplo de 6.

G: o numero obtido não é multiplo de 6. H = {6,12,18,24,30}, então G = H'

---

Uma moeda e um dado de 6 faces s˜ao lan¸cados. Seja Ω = {(K, 1),(K, 2),(K, 3),(K, 4),(K, 5),
(K, 6),(C, 1),(C, 2),(C, 3),(C, 4),(C, 5),(C, 6)}, em que K representa o resultado cara e C representa o resultado coroa. Descreva os eventos:

a) A: ocorre cara

- A = {(K, 1),(K, 2),(K, 3),(K, 4),(K, 5),(K, 6)}

b) Ocorre numero par

- B = {(K, 2),(K, 4),(K, 6),(C, 2),(C, 4),(C, 6)}

c) Ocorre o numero 3.

- C = {(K, 3),(C, 3)}

d) A &#8746; B

- D = {(K, 1),(K, 2),(K, 3),(K, 4),(K, 5),(K, 6),(C, 1),(C, 2),(C, 3),(C, 4),(C, 5),(C, 6)}

e) A &#8745; B

- E = {}

f) A'

- F = {(C, 1),(C, 2),(C, 3),(C, 4),(C, 5),(C, 6)} 

g) C'

- G = {(K, 1),(K, 2),(K, 4),(K, 5),(K, 6),(C, 1),(C, 2),(C, 4),(C, 5),(C, 6)}

---

Numa urna existem duas bolas vermelhas e seis brancas. Sorteando-se uma bola, qual a probabilidade de ela ser vermelha?

2 Bolas vermelhas e 6 brancas, totalizando 8 bolas.

P(Bola vermelha) = 2/8 = 1/4

---

Temos duas moedas, das quais uma ´e perfeita e a outra tem duas caras. Uma das moedas,
tomadas ao acaso, ´e lan¸cada. Qual ´e a probabilidade de se obter cara?

Uma moeda perfeita e uma moeda com duas caras, totalizando 3 caras.

P(Cara) = 3/4

---

De um baralho de 52 cartas, uma ´e extra´ıda ao acaso. Qual a probabilidade de cada um dos
eventos abaixo?

a) Ocorre da de copas 

- 13 cartas de copas

P(Copa) = 13/52 = 1/4

b) Ocorre dama 

- 4 damas

P(Dama) = 4/52 = 1/13

c) Ocorre carta de naipe paus

- 13 cartas de paus

P(Paus) = 13/52 = 1/4

d) Ocorre dama ou rei ou valete 

- 4 damas + 4 reis + 4 valetes = 12

P(Dama ou Rei ou Valete) = 12/52 = 3/13

e) Rei e paus 

- 4 reis e 13 paus

P(Rei e Paus) = 4/52 * 13/52 = 1/13

f) Ocorre uma carta que não é rei

- 48 cartas que não são reis

P(Não Rei) = 48/52 = 12/13

---

. Um n´umero ´e escolhido ao acaso entre os 20 inteiros, de 1 a 20. Qual a probabilidade de o
n´umero escolhido ser:

a) Par

- 10 números pares

P(Par) = 10/20 = 1/2

b) Impar

- 10 números impares

P(Impar) = 10/20 = 1/2

c) Primo

- 8 números primos

P(Primo) = 8/20 = 2/5

d) Quadrado perfeito

- 4 números quadrados perfeitos (1, 4, 9, 16)

P(Quadrado Perfeito) = 4/20 = 1/5

---

Um n´umero ´e escolhido ao acaso entre os 100 inteiros de 1 a 100. Qual a probabilidade de o
n´umero:

a) Ser multiplo de 9

- 11 números multiplos de 9

P(Multiplo de 9) = 11/100

b) Ser multiplo de 3 e de 4

- 8 números multiplos de 3 e de 4

P(Multiplo de 3 e de 4) = 8/100 = 2/25

c) Ser multiplo de 3 ou de 4

- 50 números multiplos de 3 ou de 4

P(Multiplo de 3 ou de 4) = 50/100 = 1/2

---

Liste os elementos dos seguintes espa¸cos amostrais:

a) O conjunto dos numeros naturais entre 1 e 50 divisiveis por 8

- Ω = {8, 16, 24, 32, 40, 48}

b) O conjunto de resultados quando uma moeda é jogada até que apareça uma coroa ou três caras

- Ω = {C, KC, KKC, KKK} C = coroa e K = coroa

---

Se Ω = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9}, A = {0, 2, 4, 6, 8}, B = {1, 3, 5, 7, 9}, C = {2, 3, 4, 5} e D =
{1, 6, 7}, liste os elementos dos eventos correspondentes a:

a) A ∪ C

- A ∪ C = {0,2,3,4,5,6,8}

b) A ∩ B

- A ∩ B = {}

c) ~ C 

- ~ C = {0,1,6,7,8,9}

d) (~C ∩ B ) ∪ B = {1,3,5,6,7,9}

---

Encontre os erros em cada uma das afirmações abaixo:

a) As probabilidades de que um vendedor de carros venda 0, 1, 2 ou 3 carros em qualquer dia
de fevereiro s˜ao, respectivamente, 0, 19; 0, 38; 0, 29; e 0, 15

A soma das probabilidades é maior que 1, logo está incorreto

b) A probabilidade de que choverá amanhã é de 0,4 e a probabilidade de que não chvoerá é 0,52.

Chover amanhã e não chover amanhã são eventos complementares. Logo a soma de suas probabilidades deveria ser igual a 1.

c) As probabilidades de que uma impressorá cometera 0,1,2,3,4 ou mais erros ao preparar um documento são respectivamente 0,19, 0,34 ; -0,25; 0,43; 0,29

A probabilidade de um evento deve ser um numero entre 0 e 1

d)  Em uma ´unica retirada de cartas de um baralho, a probabilidade de se tirar uma carta de
copas ´e 1
4
, a probabilidade de se tirar ma carta preta ´e 1
2
e de selecionar uma carta de copas
preta ´e de 1
8
.

A probabilidade de se tirar uma carta de copas preta é 0.


---

. Uma industria automobiliıstica estaa preocupada com um poss´ıvel recall de seu carro mais vendido.
Se houver um recall, h´a 0,25 de probabilidade de que o defeito seja no sistema de freios; 0,18 de
que seja na transmiss˜ao; 0,17 de que seja no sistema de combust´ıvel e 0,4 de que seja em alguma
outra parte.

a) Qual a probabilidade de que o defeito esteja nos freios ou no sistema de combustivel, se a probabilidade de defeitos em ambos os sistemas simultaneamente é de 0,15? 

- P(F ∪ C) = P(F) + P(C) - P(F ∩ C) = 0,25 + 0,17 - 0,15 = 0,27

onde 0,25 é a probabilidade de defeito nos freios, 0,17 é a probabilidade de defeito no sistema de combustivel e 0,15 é a probabilidade de defeito nos freios e no sistema de combustivel.

b) Qual a probabilidade de que nao haja defeitos nem no sistema de freios nem no sistema de combustivel? 

- P(F' ∩ C') = 1 - P(F ∪ C) = 1 - 0,27 = 0,73

---
Se A ´e um evento no qual um condenado cometeu assalto `a m˜ao armada e D ´e o evento no qual
o condenado vendeu drogas, enuncie em palavras as probabilidades expressas por:

a) P(A|D) 

- Probabilidade de que o condenado cometeu assalto `a m˜ao armada dado que vendeu drogas.

b) P(Ã|D)

- Probabilidade de que o condenado não cometeu assalto `a m˜ao armada dado que vendeu drogas.

c) P(~A|~D) 

- Probabilidade de que o condenado não cometeu assalto `a m˜ao armada dado que não vendeu drogas.

d) P(A|~D)

- Probabilidade de que o condenado cometeu assalto `a m˜ao armada dado que não vendeu drogas.

---

Sejam os eventos

A: O aviao parta na hora certa

B: O aviao chegue na hora certa

Sabendo que P(A) = 0,83, P(B) = 0,82 e P(A ∩ B) = 0,78, calcule:

A) O aviao chegue na hora dado que partiu na hora

- P(B|A) = P(B ∩ A) / P(A) = 0,78 / 0,83 = 0,94

B) O aviao parta na hora dado que chegou na hora

- P(A|B) = P(A ∩ B) / P(B) = 0,78 / 0,82 = 0,95

---

Uma aula de f´ısica avan¸cada tem dez estudantes do primeiro ano, 30 do ´ultimo ano e dez
formados. O resultado final mostra que trˆes dos alunos do primeiro ano, dez do ´ultimo ano e
cindo dos formados receberam um A pelo curso. Se um estudante for escolhido aleatoriamente
nessa aula e for sabido que ele recebeu um A, qual ´e a probabilidade de que seja um aluno do
´ultimo ano?

- P(U|A) = P(U ∩ A) / P(A) = 10/18 = 0,56

U = estudante do ultimo ano

A = recebeu um A

---

Uma amostra aleat´oria de 200 adultos ´e classificada pelo seu sexo e n´ıvel de instru¸c˜ao

| Nível de Instrução | Masculino | Feminino |
|-------------------|----------|----------|
| Elementar         | 38       | 45       |
| Secundário        | 28       | 50       |
| Universitário     | 22       | 17       |

Se uma pessoa desse grupo for escolhida aleatoriamente, determine a probabilidade de que:

a) A pessoa seja homem e tenha recebido educação secundaria

- P(M ∩ S) = 28/200 = 0,14

b) A pessoa não tenha nivel universitario e seja mulher

- P(~U ∩ F) = 95/200 = 0,475

Onde ~U é o complementar de U
E U é o conjunto de pessoas com nivel universitario e F é o conjunto de pessoas do sexo feminino.

c)A pessoa seja homem e tenha nivel universitario 

- P(M ∩ U) = 22/200 = 0,11

d) A pessoa seja mulher dado que tenha nivel universitario 

- P(F|U) = P(F ∩ U) / P(U) = 17/39 = 0,44

e) A pessoa tenha nivel elementar dado que seja homem

- P(E|M) = P(E ∩ M) / P(M) = 38/78 = 0,43

---
Em um experimento para estudar a rela¸c˜ao entre a hipertens˜ao e os h´abitos de fumo, foram
coletados os seguintes dados de 180 individuos:

|                   | Não Fumantes | Fumantes Moderados | Fumantes Intensos |
|-------------------|--------------|--------------------|-------------------|
| Hipertensos       | 21           | 36                 | 30                |
| Não Hipertensos   | 48           | 26                 | 19                |


a) Esteja sofrendo de hipertensão dado que é um fumante intenso.

- P(H|I) = P(H ∩ I) / P(I) = 30/49 = 0,61

b) Seja um não fumante dado que não esteja sofrendo de hipertensão.

- P(N|~H) = P(N ∩ ~H) / P(~H) = 48/93 = 0,52

c) Seja um não fumante e hipertenso

- P(N ∩ H) = 21/180 = 0,12

d) SEja um fumante intenso e hipertenso

- P(I ∩ H) = 30/180 = 0,17

---

A probabilidade de que um m´edico fa¸ca o diagn´ostico correto de uma doen¸ca ´e de 0,7. Dado
que o m´edico fez um diagn´ostico incorreto, a probabilidade de que o paciente entre com um
processo ´e de 0,9. Qual ´e a probabilidade de que o m´edico erre o diagn´ostico e seja processado
pelo paciente?

- P(E ∩ P) = P(E) * P(P|E) = 0,3 * 0,9 = 0,27

E = erro no diagnostico

P = paciente entra com um processo

---

Uma urna contem 4 bolas brancas e 3 bolas pretas. Retiram-se 3 bolas com reposi¸c˜ao. Seja X :
n´umero de bolas pretas. Determine a distribui¸c˜ao de probabilidades de X.

X: número de bolas pretas.

$X \sim B(3; 3/7)$

