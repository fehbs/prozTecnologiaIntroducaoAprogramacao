## Curso de Lógica de Programação - Bootcamp

PROZ TECNOLOGIA 

PORTAL TECH 

META 

AWS
##


#### Desafio 1) Algoritmo – Bolo de Chocolate

Ingredientes :

Massa :

1x (chá) – leite

2x (chá) – farinha de trigo

1x (chá) – achocolatado em pó

1x (chá) – óleo

2 ovos

1 colher (sopa) – fermento em pó

Calda :

1 colher (sopa) – manteiga

3 colheres (sopa) – de achocolatado em pó

3 colheres (sopa) – de açucar

1x (chá) – leite

Preparo :

1) Passo - Pré-aqueça o forno em 180 graus C .
2) Passo - Bata no litificador os ovos, o leite, o óleo, o achocolatado e o açucar.
3) Passo - Coloque os ingredientes batidos em um bowl e acrescente a farinha e o fermento e misture tudo.
4) Passo - Coloque em uma forma untada e polvilhada.
5) Passo - Levar ao forno para assar em 180 graus C , entre  30 à  40 minutos.
6) Passo - Retire o bolo do forno.
7) Passo - Misture todos os ingredientes da calda  em uma panela e leve ao fogo até ferver.
8) Passo - Faça furinhos no bolo com um garfo.
9) Passo - Regue o bolo com a calda.

##

#### Desafio 2) - Troca de diciplina e carteira em uma sala de aula.

O professor utilizou abstração; fazendo uma tabela e organizando as carteiras em 6 linhas e 6 colunas.

Depois utilizou o reconhecimento de padrões encontrando a troca na Quinta coluna; na Quinta fileira.

E a diciplina trocada foi Matemática(M) pelo Português(P).

FIGURA 2 :

4M - COLUNA 1   

2M - COLUNA 2

4M - COLUNA 3

2M - COLUNA 4

4M - COLUNA 5

2M - COLUNA 6

FIGURA 3 :

4M - COLUNA 1

2M - COLUNA 2

4M - COLUNA 3

2M - COLUNA 4

3M - COLUNA 5

2M - COLUNA 6

##

#### Desafio 3) - Instruções do projeto
Em uma inscrição, o usuário informou os seguintes dados:

- Nome: José Almeida da Silva

- CPF: 12345678900

- RG: 9517530

- Altura: 1,78

- Endereço: Rua A, 380 – Centro – Recife/PE

No algoritmo, descreva como será:

1. o identificador das variáveis;

Nome

CPF

RG

Altura

Endereço

2. a declaração das variáveis com seus respectivos identificadores e tipos de dado;

Nome: caractere

CPF: inteiro

RG: inteiro

Altura: real

Endereço: caractere

3. a utilização do comando de atribuição, apresentando identificador e dado.

Nome <- José Almeida da Silva

CPF <- 12345678900

RG <- 9517530

Altura <- 1,78

Endereço <- Rua A, 380 – Centro – Recife/PE

##

#### Desafio 4) - Elabore um algoritmo para que o usuário, através da entrada de dados, informe os seus dados pessoais.
 
Alguns desses dados
fornecidos pelo usuário precisam ser apresentados na tela quando o algoritmo for executado, são eles:
 
- Nome;

- Endereço;

- Cidade;

- CPF;

- RG.

Algoritmo "dados_do_usuario"

Var

nome : caractere

endereco : caractere

cidade : caractere 

cpf : inteiro

rg : inteiro

Inicio

escreva("Informe o seu nome :")

leia(nome)

escreva("Informe o seu endereço :")

leia(endereco)

escreva("Informe a sua cidade :")

leia(cidade)

escreva("Informe o seu CPF :")

leia(cpf)

escreva("Informe o seu RG :")

leia(rg)

escreva("Nome:", nome, ".")

escreva("Endereço:", endereco, ".")

escreva("Cidade:", cidade, ".")

escreva("CPF:", cpf, ".")

escreva("RG:", rg, ".")

Fimalgoritmo

##

### Desafios 1 e 2 CodePake 
## 
#### Desafio 1

Entender situações do cotidiano… para tomada de decisão
Elabore um algoritmo que possa descobrir, através de perguntas e respostas, em qual área de um restaurante uma pessoa ou grupo de pessoas precisa ser alocada. O restaurante tem três áreas: térreo, 1ro andar, e área externa. Clientes fumantes ou com animais de estimação precisam ser alocadas na área externa. Grupos de 5 ou mais precisam ser alocados no 1ro andar, pois não dá para juntar mesas no térreo. Qualquer outro grupo de pessoas pode ser alocado no térreo.
Algoritmo “WaiterApp”

Var

nomeDoCliente: caractere;

numeroDaMesa: inteiro;

terreo, areaExterna, primeiroAndar : inteiro;

opcoes: inteiro;

Inicio

escreva(“Bem vindo ao Sistema WaiterApp! .”)

escreva(“Informe o seu nome por favor: “)

leia(nomeDoCliente) 

escreva(“Escolha uma das opções abaixo por favor:

1)	Mesa para cinco pessoas ou mais.
2)	Mesa para fumantes ou com animais de estimação.
3)	Mesa para 1 até 4 pessoas.", opcoes)

leia(opcoes)

se(opcoes = 1) entao 

escreva(“Nome: “, nomeDoCliente, “Número da mesa: “, numeroDaMesa, “Área: “, 0)

senao

se(opcoes = 2) entao escreva(“Nome: “, nomeDoCliente, “Número da mesa: “, numeroDaMesa, “Área: “, 0)

senao

escreva(“Nome: “,nomeDoCliente, “Número da mesa: “, numeroDaMesa, “Área: “, 0)

fimse

fimalgoritmo

##
#### Desafio 2

Usar métodos de repetição… agilizar os processos
Num torneio de e-sports é necessário que todos os integrantes da mesma equipe
tenham etiquetas que os identifiquem. 

Por exemplo, se o nome da equipe é “Os Lutadores”,
o primeiro membro deve ter uma etiqueta 
“Os Lutadores – 1", o segundo membro “Os Lutadores – 2", e assim pela frente.

Elabore um algoritmo que permita ao usuário inserir o nome da equipe,
 e imprime etiquetas para os 5 membros da equipe seguindo o exemplo mostrado acima.

const nomeDaEquipe = prompt("Digite o nome da sua equipe: ");

for (let i= 1; i <= 5; i ++) {
  console.log(nomeDaEquipe + "-" + i);
  }

##









