# Lógica binária ou booleana

Também conhecida como álgebra booleana, a lógica binária é considerada como parte da lógica de matemática.
Nela temos apenas dois possíveis números `1` e `0`, também entendidos como `Verdadeiro` e `Falso`.

Usamos operadores lógicos: conjunção (`and` ou `e`) representada por `∧` , disjunção (`or` ou `ou`) representada por `∨` e a negação (`not` or `não`) representada por `¬`.
Não confundir com a álgebra elementar em que utilizamos adição, subtração, multiplicação e divisão.

## Tabela verdade

As operações básicas utilizam os operadores `and`, `or` e `not`. É essencial que esse conceito esteja bem fundamentado e
claro para todas as pessoas programadoras. Observe a tabela abaixo:

| X          | Y          | X and Y    | X or Y     |
|------------|------------|------------|------------|
| Verdadeiro | Verdadeiro | Verdadeiro | Verdadeiro |
| Verdadeiro | Falso      | Falso      | Verdadeiro |
| Falso      | Verdadeiro | Falso      | Verdadeiro |
| Falso      | Falso      | Falso      | Falso      |

Vamos analisar linha por linha:
1. Quando X é `Verdadeiro` (ou `1`) e Y também, então:
    - O resultado de X `AND` Y também é verdadeiro. O resultado é `verdadeiro` porque as duas variáveis são `VERDADEIRAS`.
    - O resultado de X `OR` Y também é verdadeiro. O resultado é `verdadeiro` porque ao menos uma variável é `VERDADEIRA`.
0. Quando X é `Verdadeiro` e Y é `Falso` (ou `0`), então:
    - O resultado de X `AND` Y será é `FALSO`. O é resultado é `falso` porque uma das duas variáveis é `FALSA`.
    - O resultado de X `OR` Y também é verdadeiro. O resultado será `verdadeiro` porque ao menos uma variável é `VERDADEIRA`.
0. Quando X é `Falso` e Y é `Verdadeiro`, então:
    - O resultado de X `AND` Y será é `FALSO`. O é resultado é `falso` porque uma das duas variáveis é `FALSA`.
    - O resultado de X `OR` Y também é verdadeiro. O resultado será `verdadeiro` porque ao menos uma variável é `VERDADEIRA`.
0. Quando X é `Falso` e Y é `Falso`, então:
    - O resultado de X `AND` Y será é `FALSO`. O é resultado é `falso` porque uma das duas variáveis é `FALSA`.
    - O resultado de X `OR` Y também é verdadeiro. O resultado será `verdadeiro` porque ao menos uma variável é `VERDADEIRA`.

A operação de negação inverte o valor da variável. Observe a tabela abaixo: 

| X          | NOT X      |
|------------|------------|
| Verdadeiro | Falso      |
| Falso      | Verdadeiro |

- Quando negamos um X `verdadeiro` o resultado dessa operação é `falso`.
- Da mesma forma, quando X é `falso` e o negamos, ele se torna verdadeiro.

## Alguns exemplos


