# Atividade Lógica proposicional

## Sumário

Este sumário tem como objetivo fornecer uma visão geral do conteúdo deste repositório e facilitar a navegação. Ele é especialmente útil para identificar rapidamente as seções relevantes e acessá-las com um único clique.

- Introdução
- Questões
- Resoluções
    - Item A
    - Item B
- Conclusão

Na conclusão do sumário, você encontrará um resumo dos resultados e descobertas desta atividade.

## Introdução

Este repositório é dedicado à atividade avaliativa de lógica proposicional, correspondente à quinta semana da segunda sprint do segundo módulo do Inteli - Instituto de Tecnologia e Liderança. O foco desta atividade é a **matemática e a física**. Neste contexto, aceitamos o desafio de explorar as complexidades e nuances da lógica proposicional e suas aplicações em computação e matemática. Através desta atividade, buscamos aprofundar nosso entendimento dos princípios fundamentais da lógica e como eles se aplicam a várias disciplinas.

## Questões

As questões que foram propostas são as seguintes:

1. Utilizando tabelas verdade, prove as seguintes equivalências. Os itens (I) e (II) são as leis de DeMorgan e têm particular importância na computação.
    - (I) $$\neg (p \land q) \Leftrightarrow \neg p \lor \neg q$$  
    - (II) $$\neg (p \lor q) \Leftrightarrow \neg p \land \neg q$$ 
    - (III) $$p \rightarrow q \Leftrightarrow \neg q \rightarrow \neg p$$ 

2. Também utilizando tabelas verdade, prove que a expressão a seguir é uma contradição.
    - $$(p \land q) \Leftrightarrow (p \rightarrow \neg q)$$

## Resoluções

### Item A

(I) $$\neg (p \land q) \Leftrightarrow \neg p \lor \neg q$$

| p | q | ¬p | ¬q | p∧q | ¬(p∧q) | ¬p∨¬q | ¬(p∧q)↔¬p∨¬q |
|---|---|----|----|-----|--------|-------|-------------|
| V | V | F  | F  | V   | F      | F     | V           |
| V | F | F  | V  | F   | V      | V     | V           |
| F | V | V  | F  | F   | V      | V     | V           |
| F | F | V  | V  | F   | V      | V     | V           |

(II) $$\neg (p \lor q) \Leftrightarrow \neg p \land \neg q$$

| p | q | ¬p | ¬q | p∨q | ¬(p∨q) | ¬p∧¬q | ¬(p∨q)↔¬p∧¬q |
|---|---|----|----|-----|--------|-------|-------------|
| V | V | F  | F  | V   | F      | F     | V           |
| V | F | F  | V  | V   | F      | F     | V           |
| F | V | V  | F  | V   | F      | F     | V           |
| F | F | V  | V  | F   | V      | V     | V           |

(III) $$p \rightarrow q \Leftrightarrow \neg q \rightarrow \neg p$$

| p | q | ¬p | ¬q | p→q | ¬q→¬p | p→q↔¬q→¬p |
|---|---|----|----|-----|-------|-----------|
| V | V | F  | F  | V   | V     | V         |
| V | F | F  | V  | F   | F     | V         |
| F | V | V  | F  | V   | V     | V         |
| F | F | V  | V  | V   | V     | V         |

### Item B

$$(p \land q) \Leftrightarrow (p \rightarrow \neg q)$$

| p | q | ¬q | p∧q | p→¬q | (p∧q)↔(p→¬q) |
|---|---|----|-----|------|-------------|
| V | V | F  | V   | F    | F           |
| V | F | V  | F   | V    | F           |
| F | V | F  | F   | V    | F           |
| F | F | V  | F   | V    | F           |

## Conclusão

Através desta atividade, conseguimos explorar a lógica proposicional e suas aplicações em detalhes. As tabelas verdade provaram ser uma ferramenta eficaz para provar equivalências e contradições. Esta atividade nos permitiu aprofundar nosso entendimento dos princípios fundamentais da lógica e como eles se aplicam a várias disciplinas. Esperamos que este repositório seja útil para quem busca entender melhor a lógica proposicional.
