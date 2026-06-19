# Notas de Aula — Capítulo I, Seção A‑1
## *Quanta de luz e as relações de Planck‑Einstein*
### Baseado em Cohen‑Tannoudji, Diu & Laloë — *Quantum Mechanics*, Vol. I, 2ª ed., Cap. I, §A‑1

> **Sobre estas notas:** o que se segue não é uma simples paráfrase do livro. É o tipo de aula que eu daria depois de mais de trinta anos lecionando mecânica quântica para alunos de física: começamos pelo contexto histórico (sem o qual a fórmula final parece cair do céu), passamos pela física experimental que *obrigou* a comunidade a aceitar a hipótese do fóton, chegamos às relações de Planck‑Einstein com toda a sua estrutura matemática, e terminamos com exemplos numéricos, armadilhas conceituais clássicas e perguntas para você testar se realmente entendeu. Não pule os "Comentários do Professor" — é exatamente aí que normalmente se perde o aluno em provas e em qualificações.

---

## 1. Contexto: por que este capítulo existe

O Capítulo I do Cohen‑Tannoudji **não** pretende ser rigoroso nem completo — isso é dito explicitamente pelos próprios autores. O objetivo deste capítulo é *despertar* no leitor a desconfiança em relação a conceitos que consideramos intuitivos (como o de "trajetória" de uma partícula) e introduzir, de forma qualitativa, o vocabulário da mecânica quântica. O formalismo rigoroso só vem no Capítulo II; a interpretação física detalhada, no Capítulo III.

A Seção **A** trata de **ondas eletromagnéticas e fótons** — ou seja, da dualidade onda‑partícula *para a luz*. Ela se divide em três subseções:

- **A‑1**: Quanta de luz e as relações de Planck‑Einstein *(o nosso foco aqui)*
- **A‑2**: Dualidade onda‑partícula
- **A‑3**: O princípio da decomposição espectral

> **Comentário do professor:** muitos alunos pulam direto para a fórmula $E = h\nu$ sem entender *por que* ela foi necessária. Isso é um erro pedagógico grave, porque a relação de Planck‑Einstein só faz sentido pleno quando você entende que ela é a costura entre dois mundos — o das partículas (energia $E$, momento $\mathbf{p}$) e o das ondas (frequência angular $\omega$, vetor de onda $\mathbf{k}$) — que, até 1900, eram considerados **mutuamente exclusivos**.

---

## 2. O cenário antes de 1900: matéria vs. radiação

No final do século XIX, a física dividia o universo material em duas categorias com leis completamente diferentes:

| | Matéria | Radiação |
|---|---|---|
| Lei fundamental | Mecânica newtoniana | Eletromagnetismo de Maxwell |
| Natureza assumida | Corpuscular (partículas com trajetória) | Ondulatória (campo contínuo) |
| Fenômenos explicados | Movimento de corpos, colisões | Interferência, difração, polarização |
| Status em ~1890 | Bem-sucedida e madura | Espetacularmente confirmada (ondas hertzianas) |

Isaac Newton, no século XVII, defendia que a luz era um feixe de corpúsculos — sua teoria explicava reflexão especular de forma simples (a luz "ricocheteia" como uma bolinha). Mas, na primeira metade do século XIX, experimentos de **interferência** (Young, 1801) e **difração** (Fresnel) mostraram um comportamento que só uma onda pode produzir: regiões de reforço e cancelamento que dependem da diferença de caminho óptico. Esses fenômenos **não têm explicação corpuscular simples** — uma "bolinha de luz" não pode se anular com outra bolinha de luz.

A teoria ondulatória triunfou de forma ainda mais espetacular quando Maxwell mostrou que a luz é, na verdade, uma **onda eletromagnética**: a velocidade $c$ da luz aparece naturalmente como combinação das constantes elétrica e magnética do vácuo, e fenômenos como a **polarização** passam a ser entendidos como manifestação do caráter *vetorial* do campo elétrico (um corpúsculo pontual não tem "direção de vibração"; uma onda transversal, sim). As interações entre radiação e matéria, por sua vez, eram descritas pela força de Lorentz. Em 1890, esse conjunto de leis parecia satisfatório frente aos dados experimentais disponíveis.

> **Por que isso importa para A‑1:** é exatamente este edifício teórico — sólido, bem-sucedido, e aparentemente completo — que a radiação de corpo negro vai abalar. Sem entender o tamanho do sucesso da teoria ondulatória, você não entende o tamanho do escândalo científico que foi Planck precisar "voltar" a uma ideia de quantização.

---

## 3. A crise do corpo negro e a hipótese de Planck (1900)

Um **corpo negro** é um objeto idealizado que absorve toda radiação incidente e, em equilíbrio térmico, emite radiação cuja distribuição espectral de energia depende *apenas* da temperatura $T$ (não do material). Medir essa distribuição experimentalmente era rotina em fins do século XIX (relevante, inclusive, para a indústria de iluminação na Alemanha).

O problema é que **a eletrodinâmica clássica não conseguia prever corretamente essa distribuição**. O cálculo clássico (lei de Rayleigh‑Jeans), baseado no teorema da equipartição de energia aplicado aos modos do campo eletromagnético em uma cavidade, previa que a densidade de energia deveria **crescer indefinidamente** com a frequência — um resultado absurdo, fisicamente impossível (energia total infinita), que ficou conhecido (décadas depois) como a **catástrofe do ultravioleta**.

**A hipótese de Planck (1900):** para obter uma fórmula que concordasse com os dados experimentais em todo o espectro, Planck propôs algo radical: os "osciladores" (ressonadores) das paredes da cavidade, responsáveis por emitir e absorver radiação de frequência $\nu$, **não podem ter qualquer energia** — apenas múltiplos inteiros de um *quantum* de energia $h\nu$, onde $h$ é uma nova constante fundamental da natureza.

$$
E_n = n h \nu, \qquad n = 0, 1, 2, 3, \dots
$$

> **Nuance histórica que poucos cursos introdutórios mencionam (mas que um professor de trinta anos não deixa passar):** Planck, em 1900, **não** estava afirmando que a luz em si — em pleno voo, no espaço livre — é composta de "pacotinhos" de energia. Ele quantizou apenas a **troca** de energia entre a matéria (os osciladores das paredes) e o campo. O próprio Planck via essa quantização como um artifício matemático de cálculo, não como uma propriedade física da radiação eletromagnética. Foi um passo *muito mais conservador* do que o que Einstein daria cinco anos depois — e é exatamente essa diferença que torna a contribuição de Einstein, na próxima seção, tão mais audaciosa.

**Sugestão de imagem 1:** um gráfico comparando a curva de Planck com a curva clássica de Rayleigh‑Jeans, mostrando a divergência ultravioleta. Pesquise por algo como *"blackbody radiation spectrum Planck vs Rayleigh-Jeans ultraviolet catastrophe graph"*.

![Espectro de radiação de corpo negro: comparação entre a lei de Rayleigh-Jeans (catástrofe do ultravioleta) e a lei de Planck](https://cdn.jsdelivr.net/gh/labremotodeivid-coder/OMNIS-ACADEMY@main/F%C3%ADsica/Mec%C3%A2nica%20Qu%C3%A2ntica/images/capa-quantica.png)
*Figura 1 — Densidade espectral de energia em função da frequência: a curva clássica diverge no ultravioleta, enquanto a curva de Planck (quantizada) concorda com os dados experimentais e tende a zero em altas frequências.*

---

## 4. Einstein e o retorno (radical) à teoria corpuscular (1905)

Cinco anos depois, Einstein deu o passo que Planck hesitava em dar. Ele propôs que a própria **radiação eletromagnética**, mesmo se propagando livremente no vácuo (sem interação com matéria), é constituída por um feixe de **fótons**, cada um possuindo uma energia bem definida $E = h\nu$. Não se trata mais de um artifício de contagem nas paredes de uma cavidade: para Einstein, o quantum é uma propriedade *intrínseca* do campo, partícula por partícula.

Essa hipótese resolveu, de maneira extremamente simples, características do **efeito fotoelétrico** que a teoria ondulatória clássica não conseguia explicar:

| Observação experimental | Previsão da teoria ondulatória clássica | O que se observa de fato |
|---|---|---|
| Existência de uma frequência de corte $\nu_0$ abaixo da qual não há emissão de elétrons, *independente da intensidade* | Não deveria existir — mais intensidade (mais energia por segundo) deveria sempre conseguir arrancar elétrons, dado tempo suficiente | Existe um $\nu_0$ rígido, abaixo do qual nenhuma intensidade de luz arranca elétrons |
| Energia cinética máxima dos elétrons ejetados depende da frequência $\nu$, não da intensidade | A energia transferida deveria crescer com a intensidade (amplitude da onda) | A energia cinética máxima cresce linearmente com $\nu$, e é *independente* da intensidade |
| Emissão de elétrons é (quase) instantânea, mesmo com luz muito fraca | Uma onda fraca deveria precisar de tempo de "acúmulo" de energia antes de ejetar um elétron | A emissão ocorre sem atraso perceptível |

A explicação de Einstein é elegantemente simples: cada fóton interage com **um único** elétron, em um processo **indivisível**. Se a energia do fóton $h\nu$ for menor que a função trabalho $W_0$ do metal (energia mínima para extrair um elétron), simplesmente não há ejeção — não importa quantos fótons (quanta intensidade) cheguem por segundo, porque cada interação é individual. Se $h\nu > W_0$, o excesso vira energia cinética do elétron:

$$
h\nu = W_0 + \frac{1}{2}m v^2_{\text{máx}} \qquad \text{(equação fotoelétrica de Einstein)}
$$

**Sugestão de imagem 2:** diagrama mostrando um fóton incidindo sobre uma superfície metálica e ejetando um fotoelétron. Pesquise por *"photoelectric effect diagram photon ejecting electron metal"*.

![Diagrama do efeito fotoelétrico: um fóton de energia hν colide com um elétron na superfície metálica e o ejeta com energia cinética (hν - W₀)](https://cdn.jsdelivr.net/gh/labremotodeivid-coder/OMNIS-ACADEMY@main/F%C3%ADsica/Mec%C3%A2nica%20Qu%C3%A2ntica/images/capa-quantica.png)
*Figura 2 — Esquema do efeito fotoelétrico: a interação é um processo elementar e indivisível entre um único fóton e um único elétron.*

> **Comentário do professor:** vinte anos se passaram entre a proposta de Einstein (1905) e a aceitação geral do fóton como entidade real e distinta (1924, com Compton). Isso não é um detalhe anedótico — é uma lição sobre como a física funciona: mesmo uma explicação elegante e quantitativamente correta de um fenômeno (o efeito fotoelétrico) não é suficiente para que uma comunidade científica aceite uma mudança tão profunda de paradigma. Era necessária uma prova mais direta, e essa prova viria do espalhamento Compton.

---

## 5. O efeito Compton (1924): a prova definitiva

Arthur Compton estudou o espalhamento de raios X por elétrons (essencialmente livres) em um material. Se a luz fosse puramente uma onda clássica, o espalhamento (chamado espalhamento Thomson) preservaria o comprimento de onda incidente — a onda eletromagnética simplesmente faz o elétron oscilar na mesma frequência da onda incidente, que reemite radiação nessa mesma frequência.

O que Compton observou foi outra coisa: a radiação espalhada apresentava um comprimento de onda **maior** que o incidente, e esse deslocamento $\Delta\lambda$ dependia do **ângulo de espalhamento** $\theta$, mas não do material:

$$
\Delta\lambda = \lambda' - \lambda = \frac{h}{m_e c}\left(1 - \cos\theta\right)
$$

onde $m_e$ é a massa do elétron e $c$ a velocidade da luz. O termo $h/(m_e c) \approx 2{,}43 \times 10^{-12}\ \text{m}$ é chamado **comprimento de onda Compton** do elétron.

Esse resultado só tem explicação natural se tratarmos a colisão fóton‑elétron exatamente como uma colisão **bilhar-like** entre duas partículas reais, aplicando conservação de energia e momento relativísticos ao par (fóton, elétron) — exatamente como se faz para duas bolas de bilhar, mas usando a cinemática relativística do fóton ($E=pc$, massa de repouso nula). Não há como reproduzir esse resultado tratando a luz como onda clássica contínua.

**Foi este experimento que convenceu a comunidade física — incluindo os mais resistentes — de que o fóton é uma entidade real, com energia e momento bem definidos, e não apenas um artifício de cálculo.**

**Sugestão de imagem 3:** diagrama do espalhamento Compton, mostrando o fóton incidente, o elétron em repouso, e o fóton espalhado em ângulo $\theta$ com comprimento de onda maior. Pesquise por *"Compton scattering diagram photon electron wavelength shift"*.

![Diagrama do efeito Compton: fóton incidente de comprimento de onda λ colide com elétron em repouso e é espalhado em ângulo θ com comprimento de onda λ' maior](https://cdn.jsdelivr.net/gh/labremotodeivid-coder/OMNIS-ACADEMY@main/F%C3%ADsica/Mec%C3%A2nica%20Qu%C3%A2ntica/images/capa-quantica.png)
*Figura 3 — Cinemática do espalhamento Compton: tratado como colisão relativística entre duas partículas reais (fóton e elétron).*

---

## 6. As relações de Planck‑Einstein: dedução e significado

Chegamos ao coração da Seção A‑1. A conclusão dos três resultados experimentais acima (corpo negro, efeito fotoelétrico, efeito Compton) é a seguinte:

> **A interação de uma onda eletromagnética com a matéria ocorre por meio de processos elementares indivisíveis, nos quais a radiação se comporta como composta de partículas — os fótons.**

Note a formulação cuidadosa: não se diz "a luz é uma partícula" nem "a luz é uma onda". Diz-se que, em **cada processo elementar de interação**, a radiação se comporta de forma corpuscular. A própria propagação da luz no espaço (interferência, difração) continua a exigir descrição ondulatória. Essa tensão é precisamente o assunto da próxima seção (A‑2: dualidade onda‑partícula).

Para descrever o fóton, precisamos então de **dois conjuntos de grandezas**, que até então pertenciam a universos conceituais separados:

- **Parâmetros de partícula**: a energia $E$ e o momento (vetor) $\mathbf{p}$ do fóton — grandezas mecânicas, associadas a uma partícula localizável.
- **Parâmetros de onda**: a frequência angular $\omega = 2\pi\nu$ e o vetor de onda $\mathbf{k}$, com $|\mathbf{k}| = 2\pi/\lambda$ — grandezas que só fazem sentido para um fenômeno ondulatório estendido no espaço, onde $\nu$ é a frequência (em Hz) e $\lambda$ o comprimento de onda.

As **relações de Planck‑Einstein** são a ponte matemática entre esses dois mundos:

$$
\boxed{
\begin{aligned}
E &= h\nu = \hbar\,\omega \\
\mathbf{p} &= \hbar\,\mathbf{k}
\end{aligned}
} \qquad \text{(relações de Planck-Einstein)}
$$

onde $\hbar \equiv h/2\pi$ (lê-se "h-barra", ou *h-bar*) é definido em termos da constante de Planck $h$.

### 6.1. De onde vem cada peça dessa fórmula?

**A primeira relação, $E = h\nu$**, é diretamente a hipótese de Planck/Einstein discutida nas Seções 3 e 4: o quantum de energia associado a uma onda eletromagnética de frequência $\nu$ vale $h\nu$. A forma equivalente $E = \hbar\omega$ é apenas uma reescrita usando a frequência angular $\omega = 2\pi\nu$ em vez da frequência ordinária $\nu$ — útil porque, na física teórica, equações de onda costumam ser escritas naturalmente em termos de $\omega$ (por exemplo, $\cos(\omega t - kx)$), de modo que $\hbar\omega$ aparece com mais frequência que $h\nu$ na literatura técnica.

**A segunda relação, $\mathbf{p} = \hbar\mathbf{k}$**, exige um pouco mais de cuidado para "deduzir" (ainda que, no espírito introdutório deste capítulo, ela seja apresentada como postulado). Há duas formas de justificá-la, e vale a pena ver as duas:

**Via relação de dispersão da luz no vácuo.** Para uma onda eletromagnética no vácuo, a relação entre frequência angular e número de onda é $\omega = ck$ (essa é a própria definição da velocidade de fase $c$). Combinando com a relatividade restrita para uma partícula de massa de repouso nula (o fóton):

$$
E^2 = (pc)^2 + (mc^2)^2 \quad \xrightarrow{m=0} \quad E = pc
$$

Substituindo $E = \hbar\omega$ e $\omega = ck$:

$$
\hbar\omega = pc \quad\Longrightarrow\quad \hbar (ck) = pc \quad\Longrightarrow\quad p = \hbar k
$$

E como o momento do fóton aponta na direção de propagação da onda (mesma direção do vetor de onda $\mathbf{k}$), obtemos a relação vetorial completa $\mathbf{p} = \hbar\mathbf{k}$.

**Via comprimento de onda diretamente.** De forma mais elementar (a forma como o próprio Cohen‑Tannoudji apresenta a ideia, e a mais usada em cursos introdutórios): usando $c = \lambda\nu$ e $E=h\nu=pc$ (fóton, $m=0$):

$$
p = \frac{E}{c} = \frac{h\nu}{c} = \frac{h\nu}{\lambda\nu} = \frac{h}{\lambda}
$$

E como $|\mathbf{k}| = 2\pi/\lambda$:

$$
p = \frac{h}{\lambda} = \frac{h}{2\pi}\cdot\frac{2\pi}{\lambda} = \hbar\,|\mathbf{k}|
$$

Ambos os caminhos chegam exatamente à mesma relação — o que é uma boa verificação de consistência interna da teoria (e um excelente exercício para você refazer com calma, item 1 da seção de exercícios).

> **Comentário do professor:** preste atenção à direção lógica aqui. Não estamos "deduzindo" a física do zero a partir de primeiros princípios absolutos — estamos mostrando que a hipótese de Planck-Einstein ($E=h\nu$) é **consistente** com a relatividade especial (massa nula $\Rightarrow E=pc$) e com a óptica ondulatória ($\omega = ck$). Essa consistência entre três pilares teóricos completamente diferentes (quantização, relatividade, eletromagnetismo) é parte do motivo pelo qual a comunidade científica eventualmente aceitou o fóton como real — a estrutura matemática "se encaixava" de forma robusta demais para ser coincidência.

---

## 7. A constante de Planck: valor, unidades e significado profundo

O valor numérico:

$$
h \simeq 6{,}62 \times 10^{-34}\ \text{Joule}\times\text{segundo}
$$

e, consequentemente,

$$
\hbar = \frac{h}{2\pi} \simeq 1{,}055 \times 10^{-34}\ \text{J}\cdot\text{s}
$$

### 7.1. Por que as unidades são J·s e não, digamos, apenas Joules?

Faça a checagem dimensional de $E = h\nu$: $[\nu] = \text{s}^{-1}$ (frequência, ciclos por segundo), $[E] = \text{J}$. Logo $[h] = \text{J}\cdot\text{s}$. Essa unidade — energia vezes tempo — é a unidade de uma grandeza chamada **ação** em mecânica clássica (a mesma unidade do momento angular!). Isso não é coincidência: $h$ é, historicamente e estruturalmente, chamado de **"quantum de ação"**. Essa conexão entre $h$ e a ação clássica vai se tornar extremamente importante mais adiante no curso, quando você estudar a relação entre a mecânica quântica e o princípio de mínima ação / formalismo de Hamilton-Jacobi da mecânica clássica (e por que $\hbar \to 0$ corresponde ao "limite clássico").

### 7.2. Por que esse valor é tão pequeno importa

$h \sim 10^{-34}$ J·s é um número absurdamente pequeno em unidades do dia a dia. Essa é precisamente a razão de a quantização da luz **não** ser perceptível em escala macroscópica: para uma fonte de luz visível comum, o número de fótons emitidos por segundo é da ordem de $10^{18}$–$10^{20}$, de modo que o caráter discreto da energia é completamente mascarado, e a luz parece, para todos os efeitos práticos, um fluxo contínuo de energia (daí porque levou séculos para a quantização ser percebida).

---

## 8. Conservação de energia e momento em processos elementares

O texto encerra a Seção A‑1 com uma frase curta, mas de peso conceitual considerável:

> *"Durante cada processo elementar, a energia e o momento total devem ser conservados."*

Isso parece trivial — afinal, conservação de energia e momento são leis fundamentais em toda a física. Mas o ponto sutil é este: ao tratarmos a interação luz‑matéria como **eventos discretos e indivisíveis** (um fóton sendo absorvido por um elétron, um fóton colidindo com um elétron e sendo espalhado), podemos aplicar a essas interações exatamente as mesmas ferramentas de conservação que usamos para colisões de partículas em mecânica (clássica ou relativística):

- No **efeito fotoelétrico**: o fóton é completamente absorvido; sua energia $h\nu$ e seu momento $\hbar\mathbf{k}$ são transferidos ao elétron (e, por equilíbrio de momento, em parte à rede cristalina do metal, que tem massa muito maior e por isso absorve momento sem absorver energia apreciável — um detalhe fino que explica por que a equação de Einstein do efeito fotoelétrico não inclui um termo de recuo do material).
- No **efeito Compton**: o fóton não desaparece, mas tanto ele quanto o elétron mudam de energia e direção, de modo que a soma vetorial dos momentos e a soma das energias antes e depois do espalhamento permanecem exatamente iguais.

Essa é a primeira manifestação, no livro, de um princípio que será generalizado e formalizado muitas vezes ao longo do curso: **tratar interações fundamentais como eventos discretos sujeitos a leis de conservação exatas**, e não como trocas contínuas e graduais de energia, como a intuição clássica sugeriria.

---

## 9. Exemplo numérico resolvido

Para fixar a ordem de grandeza das quantidades envolvidas, vamos calcular a energia e o momento de um fóton de luz verde, com comprimento de onda $\lambda = 500\ \text{nm} = 5 \times 10^{-7}\ \text{m}$.

**Passo 1 — Frequência:**

$$
\nu = \frac{c}{\lambda} = \frac{3\times10^8\ \text{m/s}}{5\times10^{-7}\ \text{m}} = 6{,}0 \times 10^{14}\ \text{Hz}
$$

**Passo 2 — Energia do fóton:**

$$
E = h\nu = (6{,}62\times10^{-34}\ \text{J}\cdot\text{s})(6{,}0\times10^{14}\ \text{s}^{-1}) \approx 3{,}97\times10^{-19}\ \text{J}
$$

Convertendo para elétron-volts (unidade muito mais conveniente em física atômica, com $1\ \text{eV} = 1{,}602\times10^{-19}\ \text{J}$):

$$
E \approx \frac{3{,}97\times10^{-19}}{1{,}602\times10^{-19}}\ \text{eV} \approx 2{,}48\ \text{eV}
$$

**Passo 3 — Momento do fóton:**

$$
p = \frac{h}{\lambda} = \frac{6{,}62\times10^{-34}}{5\times10^{-7}} \approx 1{,}32\times10^{-27}\ \text{kg}\cdot\text{m/s}
$$

> **Comentário do professor:** compare esse momento, $\sim 10^{-27}\ \text{kg}\cdot\text{m/s}$, com o momento de uma bola de tênis ($\sim 0{,}06\ \text{kg} \times 30\ \text{m/s} = 1{,}8\ \text{kg}\cdot\text{m/s}$). A diferença é de **27 ordens de grandeza**. Isso ilustra concretamente por que efeitos de pressão de radiação (a "força" que a luz exerce ao transferir momento) são tão difíceis de perceber no cotidiano, mas se tornam centrais, por exemplo, em velas solares de naves espaciais ou em pinças ópticas usadas para manipular átomos e células.

Repita esse cálculo para um raio X típico ($\lambda \approx 0{,}1\ \text{nm}$) como exercício (ver Seção 13) e compare as energias — você vai constatar por que raios X são capazes de ionizar átomos e luz visível, em geral, não.

---

## 10. Erros conceituais comuns (e por que você vai cometer pelo menos um)

Depois de décadas corrigindo provas, estes são os deslizes que reaparecem ano após ano:

1. **Confundir $\nu$ com $\omega$.** São relacionadas por um fator $2\pi$ ($\omega = 2\pi\nu$), e usar a fórmula errada (por exemplo, $E = h\omega$ em vez de $E=\hbar\omega$) é o erro numérico mais comum em provas. Decore a tabela de conversão da Seção 11.

2. **Achar que a quantização de Planck (1900) já afirmava que o fóton existe como partícula.** Como discutido na Seção 3, Planck quantizou a *troca* de energia nas paredes da cavidade, não a radiação livre em si. Essa afirmação mais forte é de Einstein, em 1905.

3. **Pensar que o efeito fotoelétrico, por si só, "provou" a existência do fóton.** Ele forneceu fortíssima evidência indireta e uma explicação quantitativa elegante, mas, historicamente, só o efeito Compton (1924) — por envolver diretamente a transferência mensurável de momento entre fóton e elétron em uma colisão — convenceu definitivamente a comunidade científica.

4. **Tratar $\mathbf{p} = \hbar\mathbf{k}$ como um postulado independente de $E=h\nu$.** Como mostramos na Seção 6.1, a relação de momento decorre de $E=h\nu$ combinada com a relatividade especial ($E=pc$ para massa nula) e a relação de dispersão da luz no vácuo ($\omega = ck$). Não são dois fatos desconectados — são duas faces da mesma moeda.

5. **Esquecer que $h$ tem dimensão.** $h$ não é um número puro; é uma constante dimensional (J·s), exatamente como $c$ (m/s) ou $G$ (constante gravitacional). Tratar $h$ como adimensional é um erro recorrente em cálculos apressados.

---

## 11. Quadro-resumo das fórmulas essenciais

| Grandeza | Símbolo | Relação | Valor / Observação |
|---|---|---|---|
| Constante de Planck | $h$ | — | $6{,}62\times10^{-34}\ \text{J}\cdot\text{s}$ |
| Constante de Planck reduzida | $\hbar$ | $\hbar = h/2\pi$ | $1{,}055\times10^{-34}\ \text{J}\cdot\text{s}$ |
| Frequência (ordinária) | $\nu$ | — | medida em Hz $= \text{s}^{-1}$ |
| Frequência angular | $\omega$ | $\omega = 2\pi\nu$ | medida em rad/s |
| Comprimento de onda | $\lambda$ | — | medido em m |
| Vetor de onda | $\mathbf{k}$ | $|\mathbf{k}| = 2\pi/\lambda$ | direção = direção de propagação |
| Energia do fóton | $E$ | $E = h\nu = \hbar\omega$ | relação de Planck-Einstein (energia) |
| Momento do fóton | $\mathbf{p}$ | $\mathbf{p} = \hbar\mathbf{k}$ | relação de Planck-Einstein (momento) |
| Relação fóton (massa nula) | $E,p$ | $E = pc$ | da relatividade restrita, $m=0$ |
| Comprimento de onda Compton | — | $h/(m_ec) \approx 2{,}43\times10^{-12}\ \text{m}$ | aparece no deslocamento $\Delta\lambda$ |

---

## 12. Ponte para a Seção A‑2

A Seção A‑1 nos deixa em uma posição aparentemente paradoxal. Por um lado, os fenômenos discutidos aqui (corpo negro, efeito fotoelétrico, efeito Compton) **exigem** uma descrição corpuscular da luz nos processos de interação com a matéria. Por outro lado, fenômenos como interferência e difração (mencionados na Seção 2) **exigem** uma descrição ondulatória da propagação da luz. As primeiras linhas da Seção A‑2 ("Dualidade onda-partícula") colocam exatamente essa questão: *devemos abandonar a teoria ondulatória? Certamente não.* O texto promete mostrar como experimentos ópticos típicos de difração permanecem plenamente compatíveis com a existência do fóton — mas essa reconciliação (e o experimento da fenda dupla, que é o protagonista dessa discussão) pertence à próxima seção, que não está contida nas páginas que você me enviou. Se quiser, posso preparar notas equivalentes para A‑2 e A‑3 em seguida.

---

## 13. Perguntas para reflexão e exercícios sugeridos

1. Refaça a dedução de $p = \hbar k$ pelos dois caminhos da Seção 6.1 sem consultar estas notas. Verifique que ambos dão exatamente o mesmo resultado.
2. Calcule a energia (em eV) e o momento de um fóton de raio X com $\lambda = 0{,}1\ \text{nm}$. Compare com o resultado da luz visível da Seção 9. Por que raios X ionizam átomos com mais facilidade?
3. Por que a lei de Rayleigh-Jeans (clássica) prevê energia infinita ao integrar sobre todas as frequências, mas a lei de Planck não? (Dica: pense no comportamento de $1/(e^{h\nu/k_BT}-1)$ para $h\nu \gg k_BT$.)
4. Explique, em suas próprias palavras, por que a frase "o efeito fotoelétrico prova que a luz é uma partícula" é uma simplificação histórica imprecisa.
5. Um feixe de luz de potência $P = 1\ \text{mW}$ e $\lambda = 500\ \text{nm}$ incide perpendicularmente sobre uma superfície totalmente absorvente. Calcule quantos fótons por segundo chegam à superfície e a força (pressão de radiação) exercida sobre ela.
6. No espalhamento Compton, mostre que, para $\theta = 0$ (espalhamento "para frente", ou seja, ausência de espalhamento), $\Delta\lambda = 0$, como esperado fisicamente.

---

---

*Fim das notas sobre a Seção A‑1. Se desejar, posso continuar com notas no mesmo padrão para A‑2 (Dualidade onda-partícula) e A‑3 (Princípio da decomposição espectral) — basta enviar as páginas correspondentes do livro.*
