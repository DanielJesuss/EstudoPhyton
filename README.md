# Estudo python
Aqui ficará todos os códigos e todas as anotações sobre os cursos de Phyton

Curso Phyton - Udemy https://www.udemy.com/course/python-desde-o-zero/learn/lecture/42515988?start=150#overview

O que é um algoritimo?
  - Sequencia de instruções lógicas
  - Chegar na solução de um problema
  - (receita de bolo por exemplo)
  - Passo a passo detalhado

Linguagem de programação?
  - Conjunto de regras, padrões e instruções para cominar com a máquina

Algoritmo VS código
  - Algoritmo: Instruções para resolver um problema
  - Código: Instruções para a máquina resolver um problema
  - Ou seja... um código é a implementação de um algoritmo

O que é Compilação?
  - Um código feito e precisa que se torne um programa executável (software)

Interpretação
  - Interprete de linguagem 
  - Diferente de compilação
  - Utiliza uma linguagem chamada bytecode
  - O interpretador vai conseguir ler e executar o bytecode

Compilar VS interpretar
  -  Código compilado pode ser executado direto no CPU (sem interpretador) - São mais rápidos
  -  Códigos interpretador são intependentes do sistema operacional - Mesmo código pode rodar em Linux, Windows, MAC ou na geladeira

<hr>

O que é Phyton?
  - Linguagem Interpretada
  - Roda em todos os SOs
  - Filosofia: Quanto mais simples melhor


O que são variáveis?
  - É um local de memória reservado que se utiliza para guardar alguma informação

a = 1 
type(a) > tipo da variável - int 
type(e) > tipo da variável - stg (string) 
type(e) >  tipo da variável - STG (string)
type(completx)  > tipo de variável - complexo 


String
  - Uma cadeia de caracteres e qualquer texto que atribuir a uma variavel 
  - Usa ' no inicio e ' no fim 
  - Tanto faz usar simples ou duplas ' ou  "  
  - Pode escrever uma string em mais de uma linha colocando ela entre parenteses ou utilizando 3 aspas simples ou dupla <br>

palavra = """curso 
de 
phyton"""

Numeros também podem ter tipso diferentes de valores inteiros ou reais (ponto flutuantes)

Atribuição de dados
  - É uma variavel é feita utilizando um simbolo de igualdade onde o lado direito é o valor que será atribuido e o lado esquerdo é a variavel que receberá esse valor 
      - Variavel = valor
  - Outro tipo de dados são booleanos, true ou false 

d = True : bool 
1 == 2 : false

<hr>

Nomenclatura de variaveis
  - Começar com letra ou underscore
  - Pode conter numeros mas não começar com eles
  - Não pode ter caracteres especiais (espaço) exceto undersocre
  - Variáveis são escritas em lowercase com separação por underscore


Entrada de dados

Utiliza a função nativa input() para receber os dados pelo usuário

nome = input('Qual seu nome?')

print('Bem vindo',nome)
ou
print(f'Bem vindo {nome}')


Funções de conversão
  - Int() converte um valor para um número inteiro
  - Float() converte um valor para um número de ponto flutuante
  - Str() converte um valor para uma string
  - Bool() converte um valor para um booleano



Operadores Aritiméticos
São os operadores para realizar cálculos matemáticos no Phyton: 

Operador
- "+" (Adição ou sinal positivo) - Soma dois valores - 10 + 4
- "-" (Subtração ou sinal negativo) -	Subtrai dois valores - 12 - 8
- "*" (Multiplicação) - Multiplica dois valores - 3 * 4
- "/" (Divisão) - Divide dois valores - 100 / 5
- "//" (Divisão inteira) - Divide dois valores e retorna apenas a parte inteira (descarta as casas decimais) - 10 // 6
- "%" (Módulo) - Retorna o resto da divisão - 4 % 2
- "**" (Exponenciação) - Eleva um número à potência de outro - 4 ** 2

<hr>

Exercicios

1: Crie um programa que solicite ao usuário o ano em que ele nasceu e calcule quantos anos ele terá no ano de 2035.

dtNascimento = int(input('Qual o ano que você nasceu: '))
idade = 2035 - dtNascimento

print(idade)

2: Desenvolva um programa que peça ao usuário para digitar um número inteiro. Em seguida, exiba o número anterior e o número seguinte.
Objetivo: Praticar operações matemáticas simples e manipulação de variáveis.

numero1 = int(input('Digite um número: ')
numero2 = numero1 - 1

print(numero2)


3: Escreva um programa que leia a largura e a altura de uma parede em metros. Calcule a área total e informe quantos litros de tinta serão necessários para pintá-la, sabendo que cada litro cobre 2 metros quadrados.

altura = int(input('Digite a altura: '))
largura = int(input('Digite a largura: '))

area = altura * largura
tinta = area / 2

print(tinta)
