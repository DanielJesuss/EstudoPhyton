# EstudoPhyton
Aqui ficará todos os códigos e todas as anotações sobre os cursos de Phyton

Curso Phyton - Udemy https://www.udemy.com/course/python-desde-o-zero/learn/lecture/42515988?start=150#overview

<h1>O que é um algoritimo?</h1>
  - Sequencia de instruções lógicas
  - Chegar na solução de um problema
  - (receita de bolo por exemplo)
  - Passo a passo detalhado

<h3>Linguagem de programação?</h3>
  - Conjunto de regras, padrões e instruções para cominar com a máquina

<h5>Algoritimo VS código</h5>
  - Algoritimo: Instruções para resolver um problema
  - Código: Instruções para a máquina resolver um problema
  - Ou seja... um código é a implementação de um algoritimo

<h5>O que é Compilação?</h5>
  - Um código feito e precisa que se torne um programa executável (software)

<h5>Interpretação</h5>
  - Interprete de linguagem 
  - Diferente de compilação
  - Utiliza uma linguagem chamada bytecode
  - O interpretador vai conseguir ler e executar o bytecode

<h5>Compilar VS interpretar</h5>
  -  Código compilado pode ser executado direto no CPU (sem interpretador) - São mais rápidos
  -  Códigos interpretador são intependentes do sistema operacional - Mesmo código pode rodar em Linux, Windows, MAC ou na geladeira

<hr>

<h3>O que é Phyton?</h3>
  - Linguagem Interpretada
  - Roda em todos os SOs
  - Filosofia: Quanto mais simples melhor


<h5>O que são variáveis?</h5>
  - É um local de memória reservado que se utiliza para guardar alguma informação

a = 1 <br>
type(a) > tipo da variável - int <br>
type(e) > tipo da variável - stg (string) <br>
type(e) >  tipo da variável - STG (string) <br>
type(completx)  > tipo de variável - complexo 


<h5>String</h5>
  - Uma cadeia de caracteres e qualquer texto que atribuir a uma variavel <br>
  - Usa ' no inicio e ' no fim <br>
  - Tanto faz usar simples ou duplas ' ou  "  <br>
  - Pode escrever uma string em mais de uma linha colocando ela entre parenteses ou utilizando 3 aspas simples ou dupla <br>

palavra = """curso 
de 
phyton"""

Numeros também podem ter tipso diferentes de valores inteiros ou reais (ponto <b>flutuantes<b>)

<h5>Atribuição de dados</h5>
  - É uma variavel é feita utilizando um simbolo de igualdade onde o lado direito é o valor que será atribuido e o lado esquerdo é a variavel que receberá esse valor <br>
      - Variavel = valor< br>
  - Outro tipo de dados são booleanos, true ou false <br>

d = True : bool <br>
1 == 2 : false

<hr>

<h3>Nomenclatura de variaveis</h3>
  - Começar com letra ou underscore<br>
  - Pode conter numeros mas não começar com eles<br>
  - Não pode ter caracteres especiais (espaço) exceto undersocre<br>
  - Variáveis são escritas em lowercase com separação por underscore<br>


<h3>Entrada de dados</h3>

Utiliza a função nativa input() para receber os dados pelo usuário

nome = input('Qual seu nome?')

print('Bem vindo',nome)
ou
print(f'Bem vindo {nome}')


<h3>Funções de conversão</h3>
  - Int() converte um valor para um número inteiro<br>
  - Float() converte um valor para um número de ponto flutuante<br>
  - Str() converte um valor para uma string<br>
  - Bool() converte um valor para um booleano
  
