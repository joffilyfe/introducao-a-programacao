# Construindo algoritmos

Talvez essa seja a seção mais divertida e ao mesmo tempo mais difícil sobre programação. É bastante comum deparar-mos com textos que pendem a criação de um algoritmo, ou que você interprete um algoritmo ou faça qualquer atividade envolvendo a palavra _algoritmo_.

## Algoritmo

> Um processo ou um conjunto de regras seguidas de cálculos ou operações que visam solucionar um problema, especificamente por um computador.

Essa é a definição do que vem a ser um _algoritmo_. Conjunto de regras.. operações.. problemas.. solução.... [:thinking:]; Por mais que esse conceito seja claro e determinístico do que vem a ser um algoritmo, quando comecei a programar eu não conseguia entender, pra mim não fazia o menor sentido.

A medida que ganhei experiência na _leitura_ de questões e problemas, eu percebi que pra mim a definição de algoritmo poderia ser algo ainda mais real:

> É a forma de organizar ideias de modo que possamos traduzi-las em uma sequência de passos. Estes serão executados por um programa ou por uma pessoa.

Um exemplo de algoritmo executado por uma pessoa seria as instruções dadas para que alguém pudesse chegar até um determinado local:
1. siga em frente até a rua X
0. depois vire a esquerda
0. continue até a rua Y
0. você chegará no seu destino

## Nosso primeiro algoritmo

Imagine que o seu chefe pediu um programa de forma urgentíssima. Os requisitos do programa são somar dois números e imprimir na tela. Antes de partirmos para a ação é preciso pensar em como traduzir o pedido em um algoritmo que o computador seja capaz de entender.

Após algum tempo pensando sobre, nós teríamos algo como:
1. receba um número digitado a partir do teclado do usuário
0. armazene o número na memória do computador
0. receba um segundo número digitado a partir do teclado do usuário
0. armazene o segundo número na memória do computador
0. obtenha os dois números a partir da memória do computador
0. some os dois números
0. armazene o resultado na memória do computador
0. obtenha o resultado a partir da memória do computador
0. exiba o resultado na tela do usuário

Dessa forma nós acabamos de escrever um algoritmo utilizando o português como linguagem. Uma humano é capaz de ler e interpretar as etapas. A próxima etapa na elaboração de um algoritmo é traduzi-lo para um idioma que um computador seja capaz de ler, interpretar e executar. Fazemos isso através das linguagens de programação.

Também é normal a utilização do [pseudo-código](https://pt.wikipedia.org/wiki/Pseudoc%C3%B3digo) quando estamos iniciando. Vejamos:

```
VARIÁVEIS
primeiro_numero
segundo_numero
total

Inicio do programa

primeiro_numero ARMAZENA entrada do teclado
segundo_numero ARMAZENA entrada do teclado

CONVERTE primeiro_numero em NÚMERO INTEIRO
CONVERTE segundo_numero em NÚMERO INTEIRO

total ARMAZENA primeiro_numero + segundo_numero

ESCREVE_NA_TELA total
Fim do programa
```

## Nosso segundo programa

Agora o seu chefe gostaria que o programa exibisse a tabuada de acordo com a entrada do teclado:

```
VARIÁVEIS
tabua_de
ultimo_numero_da_tabuada

Inicio do programa

# atribui valores as variáveis
ultimo_numero_da_tabuada ARMAZENA 10
tabua_de ARMAZENA entrada do teclado
contador ARMAZENA 1

CONVERTE tabua_de em NÚMERO INTEIRO

Enquanto contador <= ultimo_numero_da_tabuada
 ESCREVE_NA_TELA "%i x %i = %i" % (contador, tabuada_de, contador * tabuada_de)
 contador ARMAZENA contador + 1
Fim-Enquanto

Fim-do-programa
```

Suponha que você digitou `2`, então a saída do programa será:

```
1 x 2 = 2
2 x 2 = 4
3 x 2 = 6
4 x 2 = 8
5 x 2 = 10
6 x 2 = 12
7 x 2 = 14
8 x 2 = 16
9 x 2 = 18
10 x 2 = 20
```