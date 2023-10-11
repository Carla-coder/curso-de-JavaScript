vaga a1 = carro1

= sempre que tiver sinal de igual, você vai ler como "recebe"

Pense na memória do computador como um terreno de estacionamento, um espaço gigante onde posso colocar não carros, mas "dados".
Variáveis são muito parecidas com as vagas de carros. 

var = vaga => variavel.

(No JS moderno, além de utilizar a palavra var, também podemos usar a palavra let.)

Vamos criar 'identificadores':

/*"vai criar 3 espaços no meu grande terreno, que é o espaço da minha memória"*/
var n1
var n2
var n3  

Posso também colocar valores em minhas variáveis: 

var n1 =5
var n2=8.5
var n3=15

Automaticamente esses valores vão ser colocados dentro das variáveis, isso se chama de "atribuição".

E assim como as vagas de caminhões, também temos var com ''vaga maior''
usando 'string' ao invés de 'number', por isso "s" no começo da variável:

var s1 = "JavaScript'
var s2 = 'Curso em vídeo'
var s3 = `Guanabara`
	
===================================================================

O nome de cada variavel, chamamos de "identificadores"
Regras:

°Podem começar com letra, $ ou _

°Não podem começar com números
ex: não pode começar com 1s, e sim s1, senão dá erro

°E possivel usar letras ou números

°É possivel usar acentos e símbolos

°Não podem conter espaços
substitui pelo sinal de _

°Não podem ser palavras reservadas
ex: function, alert
palavras que já são utilizadas pelo JS como comandos

================================================================================

Dicas pra criar varivel´:

° Maiúsculas e minúsculas fazem diferença
se eu crio uma variável 'a' minuscula, vou ter que usar 'a' minúscula.
Se criar uma variável minuscula e usar outra variável com a letra maiuscula, dará erro no programa.
var a = 10
var A = 20

°Tente escolher nomes coerentes para variáveis
Para nome de uma pessoa: nome da variavel "nome"
Para um salário: "salário" ou "sal"
Para idade: "idade" 
telefone: "tel" "telefone"

°Evite se tornar um 'programador alfabeto' ou um 'programador contador'
O programador alfabeto é aquele que nomeia todas as variaveis dele com a,b,c,d,e,f, etc.
O programador contador é aqueles que usa  n1,n2,n3,n4,n5
Nunca faça isso!!!


================================================================================

Variaveis são pra guardar dados.

3 tipos de dados que guardamos:

5 18 -15.9 3.14 8.0
 Tipo number

true false
 Tipo booleans

"google" "javascript" "maria" "21 26975925"
 Tipo string

===================================================================================

Minhas Anotações:
Comandos em JS dentro do HTML:

<script>	window.alert //este comando emite uma mensagem! no Navegador
window.confirm //este comando faz uma pergunta de confirmação
window.prompt //este comando pede ao usúario para digitar algo 
</script>
______________________________________________________________________

Variáveis:

Como Criar variáveis: 
Ex: var nome ou let nome

Para uma variável receber um valor, usamos var nome = Gustavo /*desta forma criamos uma variável e ao mesmo tempo damos um valor a ela*/ 

nome = Gustavo /*desta forma apenas damos um valor para a variável*/

Regras das variáveis:
Podem começar com: Letra, $ ou _
Não podem começar com números 
É possível usar letras ou números
É possível usar  acentos e símbolos 
Não pode conter espaços 
Não pode usar palavras que são comandos

Dicas para nomes das variáveis: 
Maiúsculas e Minúsculas fazem a diferença!
Tente escolher nomes coerentes a função da variável. Ex: Variável que vai armazenar a idade, coloca o nome dela de “idade”
Evite se tornar um “Programador Alfabeto” ou um “Programador Contador”. Ex: Não usar os nomes das variáveis como “a”, “b”, “c”, etc; ou “a1”, “a2”, “a3”, etc.

Tipos de Dados das Variáveis: (Tipos Primitivos, lembrando que existem muitas outras!)

Numbers;
Strings;
Boolean;

Numbers: 1; -2; 4.5; 6.555 => Basicamente números
Strings: Maria, Google, Joao, pedreiro, (seu CPF) => Basicamente é uma cadeia de caracteres
Boolean: True; False 