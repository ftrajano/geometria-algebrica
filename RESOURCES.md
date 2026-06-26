# Geometria Algébrica Computacional — Resources

> **Na biblioteca local** (`biblioteca/`, fora do git): CLO 4ª ed., Lang *Algebra* 3ª ed. rev., e Gonçalves *Introdução à Álgebra* (PT) — todos em PDF. Posso citar página/seção exatas.

## Knowledge

- [Livro: *Ideals, Varieties, and Algorithms* — Cox, Little & O'Shea (CLO), 4ª ed. (2015)](https://link.springer.com/book/10.1007/978-3-031-91841-4) · **PDF na biblioteca**
  O texto-padrão de entrada para geometria algébrica computacional, em nível de graduação e **deliberadamente concreto**. **A espinha dorsal de toda a trilha.** Mapa do nosso caminho (numeração da 4ª ed.):
  - **Cap. 1** — Geometry, Algebra, and Algorithms: §1 Affine Space (p.1), **§2 Affine Varieties / operador V (p.5)**, §3 Parametrizações (p.14), **§4 Ideals / operador I (p.29)**, §5 Polinômios de uma variável (p.37).
  - **Cap. 2** — Gröbner Bases: §2 ordens monomiais (p.54), §3 algoritmo da divisão (p.61), §5 Teorema da Base de Hilbert (p.76), §7 algoritmo de Buchberger (p.90).
  - **Cap. 4** — The Algebra–Geometry Dictionary: **§1 Nullstellensatz (p.175)**, **§2 Radical Ideals & Ideal–Variety Correspondence (p.181)**, §3 somas/produtos/interseções (p.189), §4 Zariski closure / saturações (p.199), §6 decomposição em irredutíveis (p.212).
  - Cap. 5 (funções em variedades), Cap. 9 (dimensão), Cap. 10 (algoritmos modernos: F4/F5) — mais à frente.

- [Livro: *Algebra* — Serge Lang, 3ª ed. revisada (GTM 211, 2002)](https://link.springer.com/book/10.1007/978-1-4613-0041-0) · **PDF na biblioteca**
  Referência graduada, enciclopédica e **muito** densa/abstrata. **NÃO usar como texto de aprendizado no nível atual** — é seco e pressupõe fluência em provas; estudá-lo agora recria a frustração que motivou a missão. **Usar para:** consulta pontual de um enunciado mais geral *depois* de entender a versão concreta no CLO, e como meta aspiracional. Útil mais tarde para corpos/Galois e módulos.

- [Livro (grátis, CC): *Book of Proof* — Richard Hammack, 3.4 ed. (2025)](https://richardhammack.github.io/BookOfProof/)
  Introdução limpa e gratuita à **técnica de demonstração** (lógica, conjuntos, métodos de prova, indução). **Usar para:** atacar o gargalo direto — como estruturar e escrever uma prova. Caps. 4–7 e 10 são os mais relevantes agora.

- [Livro: *Introdução à Álgebra* — Adilson Gonçalves (Projeto Euclides / IMPA)](https://impa.br/) · **PDF na biblioteca** · **em português**
  Clássico brasileiro de graduação, didático e de dificuldade crescente — nível bem adequado ao usuário (oposto do Lang). **Companheiro de fundamentos em português.** Mapa de apoio às lições: Cap. III (anéis, ideais, homomorfismos) ↔ Lição 0001; Cap. IV (polinômios de uma variável, algoritmo da divisão, fatoração única) ↔ Lição 0006; Cap. V (extensões algébricas, corpo de decomposição) ↔ Lição 0005. **Limitação:** é de UMA variável e mira Teoria de Galois — **não** tem várias variáveis, variedades, Gröbner, Nullstellensatz nem Base de Hilbert. **Não substitui o CLO**; usar para reforçar pré-requisitos na língua, não para o destino geométrico/computacional.

- [Livro: *Introduction to Commutative Algebra* — Atiyah & Macdonald](https://archive.org/details/introductiontoco0000atiy)
  O clássico enxuto de álgebra comutativa. **Usar para:** mais à frente, quando CLO já estiver confortável e quisermos densidade de pós-graduação. Não começar por aqui.

- [Tutorial: *Introduction to Macaulay2* — Diane Maclagan (PDF)](https://people.maths.ox.ac.uk/agp/M2Tutorial.pdf)
  Tutorial curto e prático para começar a calcular com Macaulay2. **Usar para:** transformar teoria em cálculo verificável (bases de Gröbner, dimensão, ideais).

## Wisdom (Communities)

- [Mathematics Stack Exchange](https://math.stackexchange.com/) — tags `abstract-algebra`, `commutative-algebra`, `algebraic-geometry`.
  Alto sinal para dúvidas de estudante/prova bem formuladas. **Usar para:** validar uma demonstração que você escreveu, destravar um passo.
- [MathOverflow](https://mathoverflow.net/) — nível pesquisa.
  **Usar para:** quando a pergunta já for de fronteira (mais à frente na missão).
- [Macaulay2 Google Group / comunidade](https://macaulay2.com/) — usuários e desenvolvedores ativos.
  **Usar para:** dúvidas computacionais reais, ponte direta para a prática de pesquisa.

## Gaps
- Fundamentos em português: **coberto** por Gonçalves (anéis, ideais, polinômios de uma variável, corpos). ✓
- Ainda falta uma fonte em **português** para a parte *computacional/geométrica* (várias variáveis, variedades, Gröbner, Nullstellensatz) — Gonçalves não chega lá. Investigar notas de cursos (IMPA/USP) ou aceitar que essa parte fica em inglês via CLO.
