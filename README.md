# Atividade Lógica proposicional

Este repositório é dedicado à atividade avaliativa de lógica proposicional, correspondente à quinta semana do segundo módulo do [Inteli - Instituto de Tecnologia e Liderança](https://www.inteli.edu.br/). O foco desta atividade é a **matemática e a física**. Neste contexto, aceitamos o desafio de explorar as complexidades e nuances da lógica proposicional e suas aplicações em computação e matemática. Através desta atividade, buscamos aprofundar nosso entendimento dos princípios fundamentais da lógica e como eles se aplicam a várias disciplinas.

## Sumário

Este sumário tem como objetivo fornecer uma visão geral do conteúdo deste repositório e facilitar a navegação. Ele é especialmente útil para identificar rapidamente as seções relevantes e acessá-las com um único clique.

- [Sumário](#sumário)
- [Questões](#questões)
- [Resoluções](#resoluções)
    - [Item A](#item-a)
    - [Item B](#item-b)

Experimente clicar em um tópico para ser direcionado a ele!

## Questões

As questões que foram propostas são as seguintes:

A. Utilizando tabelas verdade, prove as seguintes equivalências. Os itens (I) e (II) são as leis de DeMorgan e têm particular importância na computação.
<br>
    - (I) $\neg (p \land q) \Leftrightarrow \neg p \lor \neg q$  
    - (II) $\neg (p \lor q) \Leftrightarrow \neg p \land \neg q$ 
    <br>
    - (III) $p \rightarrow q \Leftrightarrow \neg q \rightarrow \neg p$ 
    <br>

B. Também utilizando tabelas verdade, prove que a expressão a seguir é uma contradição.
<br>
    - $(p \land q) \Leftrightarrow (p \rightarrow \neg q)$

## Resoluções

Abaixo apresentamos as tabelas verdade referentes aos itens (I), (II) e (III) do exercício A, e ao item B.

### Item A

(I) $\neg (p \land q) \Leftrightarrow \neg p \lor \neg q$

| p | q | $\neg p$ | $\neg q$ | $p \land q$ | $\neg (p \land q)$ | $\neg p \lor \neg q$ | $\neg (p \land q) \leftrightarrow \neg p \lor \neg q$ |
|---|---|----------|----------|-------------|--------------------|----------------------|-----------------------------------------------------|
| V | V | F        | F        | V           | F                  | F                    | V                                                   |
| V | F | F        | V        | F           | V                  | V                    | V                                                   |
| F | V | V        | F        | F           | V                  | V                    | V                                                   |
| F | F | V        | V        | F           | V                  | V                    | V                                                   |

Como podemos ver, a coluna final é toda verdadeira, o que confirma que $\neg (p \land q)$ é equivalente a $\neg p \lor \neg q$.
<br>

(II) $\neg (p \lor q) \Leftrightarrow \neg p \land \neg q$

| p | q | $\neg p$ | $\neg q$ | $p \lor q$ | $\neg (p \lor q)$ | $\neg p \land \neg q$ | $\neg (p \lor q) \leftrightarrow \neg p \land \neg q$ |
|---|---|----------|----------|------------|-------------------|------------------------|------------------------------------------------------|
| V | V | F        | F        | V          | F                 | F                      | V                                                    |
| V | F | F        | V        | V          | F                 | F                      | V                                                    |
| F | V | V        | F        | V          | F                 | F                      | V                                                    |
| F | F | V        | V        | F          | V                 | V                      | V                                                    |

Como podemos ver, a coluna final é toda verdadeira, o que confirma que $\neg (p \lor q)$ é equivalente a $\neg p \land \neg q$.
<br>

(III) $p \rightarrow q \Leftrightarrow \neg q \rightarrow \neg p$

| p | q | $\neg p$ | $\neg q$ | $p \rightarrow q$ | $\neg q \rightarrow \neg p$ | $p \rightarrow q \leftrightarrow \neg q \rightarrow \neg p$ |
|---|---|----------|----------|-------------------|-----------------------------|----------------------------------------------------------------|
| V | V | F        | F        | V                 | V                           | V                                                              |
| V | F | F        | V        | F                 | F                           | V                                                              |
| F | V | V        | F        | V                 | V                           | V                                                              |
| F | F | V        | V        | V                 | V                           | V                                                              |

Como podemos ver, a coluna final é toda verdadeira, o que confirma que $p \rightarrow q$ é equivalente a $\neg q \rightarrow \neg p$.
<br>

### Item B

$(p \land q) \Leftrightarrow (p \rightarrow \neg q)$

| p | q | $\neg q$ | $p \land q$ | $p \rightarrow \neg q$ | $(p \land q) \leftrightarrow (p \rightarrow \neg q)$ |
|---|---|----------|-------------|------------------------|------------------------------------------------------|
| V | V | F        | V           | F                      | F                                                    |
| V | F | V        | F           | V                      | F                                                    |
| F | V | F        | F           | V                      | F                                                    |
| F | F | V        | F           | V                      | F                                                    |

Como podemos ver, a coluna final é toda falsa, o que confirma que $(p \land q) \Leftrightarrow (p \rightarrow \neg q)$ é uma contradição.
<br>

Através desta atividade, conseguimos explorar a lógica proposicional e suas aplicações em detalhes. As tabelas verdade provaram ser uma ferramenta eficaz para provar equivalências e contradições. Esta atividade nos permitiu aprofundar nosso entendimento dos princípios fundamentais da lógica e como eles se aplicam a várias disciplinas. Esperamos que este repositório satisfaça corretamente a atividade avaliativa .
