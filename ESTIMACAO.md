# Teoria da Estimação

Através de experimentos cientificos que se obtem novas tecnologias, novos medicamentos, novos materiais, etc.

O ato de generalizar uma parte para o todo é chamado de inferência estatística.

**Inferência Estatística**: É o processo de obtenção de conclusões sobre uma população a partir de uma amostra. Ou seja só faz sentido falar-se em inferência quando não se analisa toda a população.

Por se dispor de apenas uma parcela da população, não se é possível obter valores precisos, ao invés disso, obtem-se valores aproximados, conhecidos como estimativas.

**Estimativa**: Valor aproximado, calculado a partir de uma amostra, podendo ser intervalar ou pontual.

**Estimação**: Processo de obtenção de estimativas.

**Estimador**: Expressão algébrica que permite calcular uma estimativa.

**Parâmetro populacional**: Característica da população que se deseja estimar.

Exemplo:

Mediante uma pesquisa queremos conhecer o peso médio dos jovens entre 15 e 25 anos que habitam em Alfenas.

*   População: Jovens entre 15 e 25 anos que habitam em Alfenas.

*   Parâmetro: peso médio dos jovens.

*   Amostra: 500 jovens

*   Estimador: média amostral

*   Estimativa: 65 kg

## Estimativa Pontual

Quando se obtém uma estimativa por parametro, diz-se que é uma estimativa pontual.

Entretanto esse tipo de estimativa, sozinha é pouco informativa, pois ela não fornece uma ideia do grau de erro que se comete ao assumir o valor da estimativa como sendo igual ao do parametro desconhecido.

Esse grau de erro, pode ser quantificado da seguinte forma:

$P[a < \theta < b] = \gamma$

Onde:

$\gamma$ = 1 - $\alpha$

$\alpha$ = Probabilidade de se cometer o erro do tipo I

A probabilidade $\gamma$ mede o grau de confiânça, que se tem na estimação de $\theta$.

Os intervalos $[a,b]$ são chamados de intervalos de confiânça.

O ideal é que se tenha valores de $\gamma$ altos, intervalos de confiança pequenos, estreitos, assim tendo uma ideia muito proxima do valor de $\theta$.

## Estimativa Intervalar

Quando se obtém uma estimativa por intervalo, diz-se que é uma estimativa intervalar.

$IC_{1-α}(µ) = \left( X̄ - z\left(\frac{α}{2}\right) \frac{rσ^2}{n}, X̄ + z\left(\frac{α}{2}\right) \frac{rσ^2}{n} \right)$


Através do teorema central do limite, pode-se chegar que $100(1-α)\%$ das vezes, a média amostral estará contida no intervalo de confiança.

### Teorema Central do Limite

Seja uma população descrita por uma variavel $X$ com distribuição qualquer, com uma média $\mu$ e uma variância $\sigma^2$ diferente da normal. Se infinitas amostras do tamanho n são coletadas nessa população, então a média amostral $\bar{X}$ terá uma distribuição aproximadamente normal com média $\mu$ e variância $\frac{\sigma^2}{n}$.

Em práticas reais, não se tem o valor exato de $\sigma^2$, então usa-se $S^2$ como estimativa de $\sigma^2$.

A média segue então, dessa forma uma distribuição conhecida como t-student.

$IC_{1-α}(µ) = \left( X̄ - t\left(\frac{α}{2}, n-1\right) \frac{rS^2}{n}, X̄ + t\left(\frac{α}{2}, n-1\right) \frac{rS^2}{n} \right)$

Existe $100(1-α)\%$ de chance de a média amostral estar contida no intervalo de confiança.

### Exemplo

Um pesquisador deseja saber qual a quantidade do principio ativo de um determinado farmaco. Em uma pesquisa, uma amostra aleatoria de 8 frascos foram analisados e se obteve uma média de 4,75mg e desvio padrão de 1,83mg. Assumindo que a quantidade do principio ativo segue uma distribuição normal, encontre o intervalo de 95% para a quantidade média de principio ativo do farmaco e interprete.

$\bar{X} = 4,75$ = MÉDIA

$S = 1,83$ = DESVIO PADRÃO

Foi informado que o nivel de confiança é de 95%, ou seja o valor de $\alpha$ é de 5%.

$\alpha = 0,05$

Portanto $\frac{\alpha}{2} = 0,025$

Assim, $t\left(\frac{α}{2}, n-1\right) = t\left(0,025, 7\right) = 2,365$

onde n é o tamanho da amostra.

Esse valor obtido foi através da tabela da distribuição t-student.

Portanto $me$ = 2,365 x $\frac{1,83}{\sqrt{8}}$ = 1,53mg.

Portanto

$IC_{1-α}(µ) = \left( 4,75 - 1,53, 4,75 + 1,53 \right)$

$IC_{1-α}(µ) = \left( 3,22, 6,28 \right)$

Existe 95% de chance de a média amostral estar contida no intervalo de confiança.

