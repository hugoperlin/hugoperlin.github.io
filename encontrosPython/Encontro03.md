# Encontro 03

No encontro de hoje iremos falar sobre:
1. Variáveis
2. Números em Python
3. Como fazer contas
4. Um pequeno programa
5. Desafio

## 1. Variáveis

As variáveis são locais onde o python armazena os dados de nossos programas. Você pode pensar em uma variável como uma caixinha onde você pode armazenar coisas dentro. Essas coisas são os dados que os programas manipulam.
Nós já criamos variáveis em nossos programas, para armazenar o nome, a idade, as *turtles*, etc. As variáveis conseguem armazenar números e textos. 

Um texto sempre deverá estar entre " ".

Veja o programa abaixo, ele cria duas variáveis, uma para armazenar o nome e outra a idade.

```python

nome = "Hugo Alberto Perlin"
idade = 36

```

Para criar uma variável é bem fácil, precisamos de dois passos:
1. Um nome: toda variável possui um nome. Pense nesse nome como uma etiqueta que você coloca na caixa para lembrar o que tem dentro. O nome de uma variável sempre deve começar com uma letra, depois pode usar letras e números. Não pode utilizar espaço, acentos ou outro símbolos (%,\$,@,...)
2. Atribuir: para você guardar alguma coisa em uma variável utilizamos o sinal de = 


Vamos relembrar do exercício que pedia para o usuário digitar o nome e a idade. 

1. Abra o Idle 
2. Clique em File -> New
3. Copie o código abaixo
4. Clique em Run
5. Salve o seu arquivo com o nome **encontro0301.py**
6. Digite os valores pedidos

```python

nome = input("Digite seu nome:")
idade = input("Digite sua idade:")

print("Olá ",nome,", você tem",idade)

```

## 2. Números

Em Python podemos trabalhar com números, que podem ser inteiros e decimais. Os números inteiros são aqueles valores que não são quebrados (5, 10, 200, 2, etc). Os números decimais tem partes quebradas (1,5, 2,5, 3,1, etc).

Como Python é uma linguagem baseada em inglês, para representar números decimais trocamos a , por . Então os números ficam (1.5, 2.5, 3.1, etc)

Para ler números digitados pelo usuário, temos que utilizar a operação *eval()*. Ela irá converter um texto em um número.

Vamos refazer o exercício anterior, agora vamos calcular quantos anos o usuário terá daqui 10 anos.

1. No Idle 
2. Clique em File -> New
3. Copie o código abaixo
4. Clique em Run
5. Salve o seu arquivo com o nome **encontro0302.py**
6. Digite os valores pedidos

```python

nome = input("Digite seu nome:")
idade = eval(input("Digite sua idade:"))

idadeMais10 = idade + 10

print("Olá "+nome+", hoje você tem "+idade+" anos")
print("Daqui 10 anos, você terá "+idadeMais10)

```

## 3. Como fazer contas

Os computadores são muito bons em armazenar dados e fazer contas. Nossos computadores consegue fazer bilhões de contas por segundo!! Em Python temos os seguintes operadores para realizar operações matemáticas:

| Operador      | Operação      | Exemplo |
| :------------:|:-------------:| :-----:  |
| +             | soma          | 2 + 2   |
| -             | subtração     | 5 - 3   |
| /             | divisão       | 10 / 2  |
| *             | multiplicação | 2 + 2   |


Vamos fazer algumas contas:

1. No shell do Idle (aquela tela onde aparece o resultado das operações) 
2. Digite as seguintes operações:

15 + 10

500 + 900

5 - 3

1987 - 3

10 / 5

8 / 4

5 / 2

5 * 2

10 * 3

## 4. Um pequeno programa


Vamos fazer um pequeno programa para treinar o que aprendemos hoje. 
Sua mãe pediu para você ir na frutaria e comprar 2 abacaxis, 5 laranjas, 3 bananas e 4 pessêgos. Na frutaria tem uma placa com os seguintes valores: 
      Abacaxi - R$ 2,50 cada
      Laranaja - R$ 0,75 cada
      Banana   - R$ 1,00 cada
      Pessêgo  - R$ 3,00 cada
      
Faça um programa que calcule o total da compra.


1. No Idle 
2. Clique em File -> New
3. Copie o código abaixo
4. Clique em Run
5. Salve o seu arquivo com o nome **encontro0303.py**
6. Digite os valores pedidos


```python

#declaração das variáveis para armazenar os preços das frutas
valorAbacaxi = 2.5
valorLaranja = 0.75
valorBanana = 1.00
valorPessego = 3.00

totalAbacaxis = valorAbacaxi * 2
totalLaranjas = valorLaranja * 5
totalBananas = valorBanana * 3
totalPessegos = valorPessego * 4


totalCompra = totalAbacaxis + totalLaranjas + totalBananas + totalPessegos


print("O total da sua compra foi R$", totalCompra")

```

## 5. Desafio

Modifique o programa anterior, e ao invés de deixar o número de cada fruta fixo (escrito no código), pergunte para o usuário.


```python

```
