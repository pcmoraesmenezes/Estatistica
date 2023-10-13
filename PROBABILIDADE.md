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

