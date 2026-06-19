# Capítulo 1 — Ondas e Partículas

# Introdução às Ideias Fundamentais da Mecânica Quântica

---

# Introdução

## Por que a Mecânica Quântica existe?

Uma teoria física surge quando as teorias anteriores deixam de explicar determinados fenômenos observados experimentalmente.

A Mecânica Quântica nasceu exatamente dessa necessidade.

Durante os séculos XVIII e XIX, a Física era dominada por duas teorias extraordinariamente bem-sucedidas:

1. A Mecânica de Newton;
2. O Eletromagnetismo de Maxwell.

Juntas, essas teorias eram capazes de explicar praticamente todos os fenômenos conhecidos na época.

A mecânica descrevia o movimento dos corpos.

O eletromagnetismo descrevia:

* eletricidade;
* magnetismo;
* luz.

Parecia que a Física estava praticamente completa.

Contudo, no final do século XIX começaram a surgir experimentos cujos resultados não podiam ser explicados pela Física Clássica.

Esses experimentos revelaram que a matéria e a radiação apresentam comportamentos completamente diferentes daqueles previstos pelas teorias clássicas.

A consequência foi profunda:

> As leis clássicas não são universais.

Elas constituem apenas uma aproximação válida para sistemas macroscópicos.

Quando investigamos fenômenos em escalas atômicas e subatômicas, uma nova teoria torna-se necessária.

Essa nova teoria é a Mecânica Quântica.

---

## O domínio de validade da Física Clássica

É importante compreender que a Mecânica Quântica não substitui a Mecânica Clássica.

A Mecânica Clássica continua correta dentro do seu domínio de aplicação.

Por exemplo:

* movimento de planetas;
* lançamento de projéteis;
* movimento de automóveis;
* vibrações mecânicas;
* dinâmica de fluidos.

Todos esses fenômenos envolvem escalas muito maiores que as escalas atômicas.

Nessas situações, as previsões quânticas convergem para as previsões clássicas.

Esse resultado é conhecido como:

### Princípio da Correspondência

Quando os sistemas tornam-se suficientemente grandes, a Mecânica Quântica reproduz a Mecânica Clássica.

---

## Dois Grandes Problemas da Física Clássica

No início do século XX, dois conjuntos de fenômenos exigiam explicação:

### Problema 1 — Estrutura da Matéria

A Física Clássica não conseguia explicar adequadamente:

* estabilidade dos átomos;
* espectros atômicos;
* ligações químicas.

Segundo a eletrodinâmica clássica, elétrons acelerados deveriam emitir radiação continuamente.

Como consequência, os elétrons deveriam perder energia e colapsar sobre o núcleo.

Isso implicaria:


$$\text{átomos instáveis}$$


Entretanto, os átomos são estáveis.

Portanto havia algo fundamentalmente errado.

---

### Problema 2 — Natureza da Radiação

A teoria eletromagnética de Maxwell descrevia a luz como uma onda.

Essa interpretação explicava perfeitamente:

* interferência;
* difração;
* polarização.

Contudo, vários experimentos indicavam que a luz também apresentava características tipicamente corpusculares.

A questão tornou-se:

> Afinal, a luz é uma onda ou uma partícula?

A resposta da Mecânica Quântica será surpreendente:

> A luz possui simultaneamente características ondulatórias e corpusculares.

---

# A. Ondas Eletromagnéticas e Fótons


![Texto Alternativo](https://cdn.jsdelivr.net/gh/labremotodeivid-coder/OMNIS-ACADEMY@main/Física/Mecânica%20Quântica/images/capa-quantica.png)

---

# A.1 Quanta de Luz e Relações de Planck-Einstein

## A visão de Newton

Durante o século XVII, Newton defendia uma teoria corpuscular para a luz.

Segundo essa hipótese, a luz seria composta por partículas emitidas pela fonte luminosa.

```md
[IMAGEM: Representação da teoria corpuscular de Newton]
```

Essa teoria explicava naturalmente:

* propagação retilínea;
* reflexão;
* parte da refração.

Por muito tempo essa interpretação foi considerada satisfatória.

---

## O Surgimento da Teoria Ondulatória

Durante o século XIX, experimentos realizados por Young e Fresnel demonstraram que a luz apresenta fenômenos característicos de ondas.

Entre eles:

### Interferência

Quando duas ondas se superpõem, pode ocorrer reforço ou cancelamento.

Matematicamente:


$$E_{total}=E_1+E_2$$

Como a intensidade observada é proporcional ao quadrado da amplitude,

$$
I \propto |E_{total}|^2
$$

surgem regiões claras e escuras.

```md
[IMAGEM: Experimento da dupla fenda de Young]
```

A presença dessas franjas não pode ser explicada por partículas clássicas.

---

### Difração

Outra evidência importante é a difração.

Uma onda atravessando uma abertura estreita espalha-se pelo espaço.

```md
[IMAGEM: Difração por fenda única]
```

Esse comportamento é natural para ondas.

Partículas clássicas não apresentam esse efeito.

---

## A Síntese de Maxwell

O trabalho de Maxwell mostrou que a luz é uma onda eletromagnética.

As equações de Maxwell preveem que perturbações eletromagnéticas propagam-se com velocidade

$$
c=
\frac{1}{\sqrt{\mu_0\varepsilon_0}}
$$

onde:

* $\mu_0$ é a permeabilidade do vácuo;
* $\varepsilon_0$ é a permissividade do vácuo.

Substituindo os valores experimentais:

$$
\mu_0
=====

4\pi\times10^{-7}
;H/m
$$

$$
\varepsilon_0
=============

8.854\times10^{-12}
;F/m
$$

obtemos

$$
c
\approx
3.00\times10^8
;m/s
$$

exatamente a velocidade da luz.

Esse resultado foi considerado uma das maiores conquistas da Física do século XIX.

Parecia que a natureza da luz estava definitivamente compreendida.

Mas não estava.

---

## O Problema da Radiação de Corpo Negro

No final do século XIX surgiu uma contradição grave.

A teoria clássica previa uma distribuição espectral incompatível com os experimentos.

A lei clássica de Rayleigh-Jeans fornecia:

$$
u(\nu,T)
========

\frac{8\pi\nu^2k_BT}{c^3}
$$

Observe o fator

$$
\nu^2
$$

Quando a frequência cresce indefinidamente,

$$
\nu\rightarrow\infty
$$

temos

$$
u(\nu,T)\rightarrow\infty
$$

A teoria previa emissão infinita de energia.

Esse resultado absurdo ficou conhecido como

### Catástrofe Ultravioleta

```md
[IMAGEM: Curva experimental versus Lei de Rayleigh-Jeans]
```

A Física Clássica havia falhado.

---

## A Hipótese de Planck

Em 1900, Max Planck propôs uma hipótese revolucionária.

Ele assumiu que os osciladores materiais não poderiam trocar energia de maneira contínua.

A energia deveria ser emitida em pacotes discretos.

Esses pacotes foram chamados de quanta.

Os valores permitidos seriam

$$
E_n=n h\nu
$$

onde

$$
n=0,1,2,3,...
$$

e

$$
h=6.62607015\times10^{-34}
;J\cdot s
$$

é a constante de Planck.

---

## O Significado da Quantização

Na Física Clássica:

```text
Energia:
0 → qualquer valor → infinito
```

Na Física Quântica:

```text
Energia:
0
hν
2hν
3hν
4hν
...
```

A energia não varia continuamente.

Ela varia em degraus.

Essa ideia simples inaugurou toda a Mecânica Quântica.

---

## Einstein e os Fótons

Em 1905 Einstein deu um passo ainda mais radical.

Ele propôs que a própria radiação eletromagnética é composta por partículas.

Essas partículas receberam posteriormente o nome de:

### Fótons

Cada fóton transporta uma quantidade definida de energia.

Einstein propôs então:

$$
E=h\nu
$$

Essa é a primeira Relação de Planck-Einstein.

---

## Interpretação Física da Relação

A expressão

$$
E=h\nu
$$

mostra que a energia é proporcional à frequência.

Se duplicarmos a frequência:

$$
\nu\rightarrow2\nu
$$

então

$$
E\rightarrow2E
$$

Se triplicarmos a frequência:

$$
\nu\rightarrow3\nu
$$

então

$$
E\rightarrow3E
$$

Portanto:

> Quanto maior a frequência da radiação, maior a energia transportada por cada fóton.

Essa é a razão pela qual raios X são muito mais energéticos que a luz visível.

---

## Forma Angular da Relação

Definimos a frequência angular

$$
\omega=2\pi\nu
$$

Isolando:

$$
\nu=\frac{\omega}{2\pi}
$$

Substituindo em

$$
E=h\nu
$$

obtemos

$$
E=h\frac{\omega}{2\pi}
$$

Definimos então

$$
\hbar=\frac{h}{2\pi}
$$

onde

$$
\hbar
=====

1.054571817\times10^{-34}
;J\cdot s
$$

Finalmente,

$$
E=\hbar\omega
$$

forma utilizada em praticamente toda a Mecânica Quântica moderna.

---

## Momento Linear do Fóton

A segunda relação fundamental de Planck-Einstein é

$$
p=\hbar k
$$

onde

$$
k=\frac{2\pi}{\lambda}
$$

é o número de onda.

Substituindo:

$$
p=
\hbar\frac{2\pi}{\lambda}
$$

Como

$$
\hbar=\frac{h}{2\pi}
$$

segue que

$$
p=
\frac{h}{\lambda}
$$

Essa equação mostra que a luz transporta momento linear mesmo não possuindo massa de repouso.

Essa conclusão terá consequências profundas em toda a Mecânica Quântica.

---

## Resultado Fundamental da Seção

As relações

$$
E=h\nu
$$

$$
E=\hbar\omega
$$

$$
p=\hbar k
$$

$$
p=\frac{h}{\lambda}
$$

constituem a ponte entre a descrição ondulatória e a descrição corpuscular da radiação.

Elas representam o primeiro passo para a compreensão da dualidade onda-partícula.
