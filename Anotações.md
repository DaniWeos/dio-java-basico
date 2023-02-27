<h1>Anotações pessoais</h1>

>-Toda classe deve ser criada na pasta src. </br>
>-Nome do arquivo deve começar com letra maiúscula, as próximas palavras também devem começar. </br>
>Ex: Calculadora.java / CalculadoraCientifica.java</br>

-Toda variável a ser criada deve ser minúscula, se for composta, as próximas palavras devem começar com letra maiúscula. </br> 
Ex: janela / janelaFechada </br>
-Regra de variáveis: </br>
	-Nunca usar simbólos, exceto $ e _ (underline). Nunca usar espaço ( ), nunca usar palavras reservadas (void,long,int) e nunca começar com números (1variavel).
Toda vez que eu tiver algo a ser executado, construo na minha main. 
Como declarar:
Variável: tipo NomeBemDefinido: atribuição,valor;
Ex: Int ano: 2000;
Método: tipo NomeNoInfinitivo (Parâmetros)
Ex: Int somar (int valor1, int valor2)
Como diferenciar uma variável de um método? Métodos sempre vem acompanhado de um parâmetro: 
Ex: String nomeCompleto = nomeCompleto (PrimeiroNome , segundoNome);

Como criar um package de forma correta:
Selecionar a pasta src;
Depois criar uma nova pasta com o tema abrangente, exemplo com, org, edu.
Dentro da pasta edu criar o nome do projeto em geral, exemplo appPesquisa
Dentro do appPesquisa criar as pastas subsequentes do desenvolvimento, exemplo layout, calculo.
Ficará assim: src/com/appPesquisa/layout
              src/com/appPesquisa/calculo

Variáveis do tipo float devem terminar com um F no final, e do tipo long com um L no final. Ex:
float pi = 3,14F;
long cpf = 98765432109L;
Para declarar uma constante (variável cujo valor NUNCA pode ser alterado) deve se colocar o nome final antes do tipo da variável, e a variável deve ser toda em MAIÚSCULA. 
Ex: final double PI = 3,14;

Atribuindo valores:
String nome = “Daniel”
double peso  = 60.5;
char sexo = ‘M’;
boolean doadorOrgao = true;
Date dataNascimento = new Date();

Operadores
atribuição: =
adição: +
subtração: - 
multiplicação: *
divisão: /
modulo: % (encontrar o resto)
negação: !
incremento: ++
decremento: -- 
maior que: >
maior igual que: >=
menor igual que: <=
menor que: <
diferente: !=
igual: ==
Como converter um numero positivo para negativo?
	numero =  - numero;
Como converter para positivo?
numero = numero * -1;
Invertendo váriaveis booleanas:
boolean variavel = true;
variavel = !variavel;
Conjunção(&&) : Só é verdadeiro se ambos são verdadeiros, e é falso se houver pelo menos um falso.
Disjunção(||): Só é falso quando ambas são falsas
Disjunção exclusiva(^): Só é verdade quando ambos são opostos


Como nomear um Método: sempre um verbo: Frear, buzinar, concluir.
Padrão camelCase: primeiraMiniscula, segundaMaiuscula.
NÃO EXISTE MÉTODO GLOBAL.
Para criar um método devo me perguntar: Qual a finalidade dele? Qual o retorno ele deve me dar?
Caso o método não retorne nenhum valor, retornará void.
Uma variavel de classe pode ser acessada por todos os métodos.
Uma variavel de método só esta visivel e podera ser usada por esse metodo.,

Scanner: receber entradas do usuário

LAÇOS DE REPETIÇÃO


Decisão: if, if-else, if-else-if, switch e ternário
Repetição: for, while, do while
Interrupção: Break, continue, return
Repetição com teste no inicio: While
Repetição com teste no final: do-While
Repetição contada: for

BLOCOS
Locais: dentro de métodos
Estáticos: dentro de classes
Instância: dentro de classes
