<h1>Anotações pessoais</h1>

>-Toda classe deve ser criada na pasta src. </br>
>-Nome do arquivo deve começar com letra maiúscula, as próximas palavras também devem começar. </br>
>Ex: Calculadora.java / CalculadoraCientifica.java</br>

>-Toda variável a ser criada deve ser minúscula, se for composta, as próximas palavras devem começar com letra maiúscula. </br> 
Ex: janela / janelaFechada </br>
+Regra de variáveis: </br>
-Nunca usar simbólos, exceto $ e _ (underline). </br>
-Nunca usar espaço ( ), nunca usar palavras reservadas (void,long,int) e nunca começar com números (1variavel).</br>
-Toda vez que eu tiver algo a ser executado, construo na minha main. </br>
-Como declarar:</br>
-Variável: tipo NomeBemDefinido: atribuição,valor;</br>
-Ex: Int ano: 2000;</br>
-Método: tipo NomeNoInfinitivo (Parâmetros)</br>
-Ex: Int somar (int valor1, int valor2)</br>
-Como diferenciar uma variável de um método? Métodos sempre vem acompanhado de um parâmetro: </br>
-Ex: String nomeCompleto = nomeCompleto (PrimeiroNome , segundoNome);</br>

>-Como criar um package de forma correta:</br>
-Selecionar a pasta src;</br>
-Depois criar uma nova pasta com o tema abrangente, exemplo com, org, edu.</br>
-Dentro da pasta edu criar o nome do projeto em geral, exemplo appPesquisa</br>
-Dentro do appPesquisa criar as pastas subsequentes do desenvolvimento, exemplo layout, calculo.</br>
-Ficará assim: src/com/appPesquisa/layout</br>
              src/com/appPesquisa/calculo</br>

>-Variáveis do tipo float devem terminar com um F no final, e do tipo long com um L no final. Ex:</br>
-float pi = 3,14F;</br>
-long cpf = 98765432109L;</br>
-Para declarar uma constante (variável cujo valor NUNCA pode ser alterado) deve se colocar o nome final antes do tipo da variável, e a variável deve ser toda em -MAIÚSCULA. </br>
-Ex: final double PI = 3,14;</br>

>-Atribuindo valores:</br>
-String nome = “Daniel”</br>
-double peso  = 60.5;</br></br>
-char sexo = ‘M’;</br>
-boolean doadorOrgao = true;</br>
-Date dataNascimento = new Date();</br>

>*Operadores</br>
-atribuição: =</br>
-adição: +</br>
-subtração: - </br>
-multiplicação: *</br>
-divisão: /</br>
-modulo: % (encontrar o resto)</br>
-negação: !</br>
-incremento: ++</br>
-decremento: -- </br>
-maior que: ></br>
-maior igual que: >=</br>
-menor igual que: <=</br>
-menor que: <</br>
-diferente: !=</br>
-igual: ==</br></br>
-Como converter um numero positivo para negativo?</br>
	numero =  - numero;</br>
-Como converter para positivo?</br>
-numero = numero * -1;</br>
-Invertendo váriaveis booleanas:</br>
-boolean variavel = true;</br>
-variavel = !variavel;</br>
-Conjunção(&&) : Só é verdadeiro se ambos são verdadeiros, e é falso se houver pelo menos um falso.</br>
-Disjunção(||): Só é falso quando ambas são falsas</br>
-Disjunção exclusiva(^): Só é verdade quando ambos são opostos</br>

>-Como nomear um Método: sempre um verbo: Frear, buzinar, concluir.</br></br>
-Padrão camelCase: primeiraMiniscula, segundaMaiuscula.</br>
-NÃO EXISTE MÉTODO GLOBAL.</br>
-Para criar um método devo me perguntar: Qual a finalidade dele? Qual o retorno ele deve me dar?</br>
-Caso o método não retorne nenhum valor, retornará void.</br>
-Uma variavel de classe pode ser acessada por todos os métodos.</br>
-Uma variavel de método só esta visivel e podera ser usada por esse metodo.,</br>

>-Scanner: receber entradas do usuário</br>

<h1> LAÇOS DE REPETIÇÃO </h1>


>-Decisão: if, if-else, if-else-if, switch e ternário</br>
-Repetição: for, while, do while</br>
-Interrupção: Break, continue, return</br>
-Repetição com teste no inicio: While</br>
-Repetição com teste no final: do-While</br></br>
-Repetição contada: for</br>

>-BLOCOS</br>
-Locais: dentro de métodos</br>
-Estáticos: dentro de classes</br>
-Instância: dentro de classes</br>
