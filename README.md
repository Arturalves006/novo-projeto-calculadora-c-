## Calculadora Científica em C

> Uma calculadora completa em linguagem C, com suporte a operações matemáticas básicas e avançadas, funções trigonométricas, logaritmos, operações de matriz (2x2 e 3x3) e armazenamento de histórico de cálculos.
>
## Como usar

Compile o código com um compilador C, por exemplo:

> gcc calculadora.c -o calculadora -lm


Obs.: O -lm é necessário para usar funções matemáticas da biblioteca math.h.

Execute o programa:

>./calculadora


Siga as instruções no menu para escolher a operação desejada.

>Para sair do programa, escolha a opção 0.

## Funcionalidades
### Operações Básicas

Soma

Subtração

Multiplicação

Divisão (com verificação de divisão por zero)

### Operações Avançadas

Potência

Raiz quadrada

Logaritmo natural (ln)

Logaritmo base 10

Exponencial (e^x)

Fatorial

Valor absoluto

Arredondamentos (ceil, floor, round)

Conversões entre graus ↔ radianos

Cálculo da hipotenusa

Área de um círculo

### Funções Trigonométricas

Seno

Cosseno

Tangente

### Operações com Matrizes (3x3)

Soma de matrizes

Multiplicação de matrizes

### Histórico de Cálculos

Armazena até 100 operações

Permite consultar todas as operações realizadas 

## Observações

A calculadora aceita múltiplos números para soma, subtração, multiplicação e divisão.

O histórico guarda os últimos 100 cálculos realizados.

Operações com matrizes só funcionam para matrizes 3x3.

Algumas funções exigem que o número seja positivo (como logaritmo e raiz quadrada).

Operações como divisão por zero são tratadas com mensagem de erro.
