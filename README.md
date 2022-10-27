##  Lógica Imperativa - Bootcamp

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

### Desafios 1 e 2 CodePark 
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
##

##  Introdução a programação
##

### Desafios_CodePark
##

### Desafio_1

INSTRUÇÕES DO PROJETO

Desenvolva um programa que utiliza o nome de um aluno, duas notas e a quantidade de faltas que ele teve. Conclua se o aluno está aprovado ou reprovado de acordo com as especificações:

- Se a média do aluno for menor que sete, o sistema deve informar o nome do aluno e que ele está reprovado;
- Se o aluno possuir mais de três faltas, o sistema deve informar o nome do aluno e que ele está reprovado; 
- Se a média do aluno for maior ou igual a sete, o sistema deve informar o nome do aluno e que ele está aprovado. 

No sistema, todos os valores devem estar armazenados em variáveis.


studentName = str(input("Nome do aluno: "))

note1 = float(input("Primeira nota: "))

note2 = float(input("Segunda nota: "))

faults = int(input("Quantidade de faltas: "))

average = (note1 + note2) / 2

if average < 7 or faults > 3:
    print("Nome:", studentName, ", reprovado.")

else:
print("Nome:", studentName, 
", aprovado!")

##


### Desafio_2

INSTRUÇÕES DO PROJETO
Desenvolva um código que utilize as seguintes características de um veículo:
- Quantidade de rodas;
- Peso bruto em quilogramas;
- Quantidade de pessoas no veículo.

Com essas informações, o programa mostrará qual é a melhor categoria de habilitação para o veículo informado a partir das condições:
A: Veículos com duas ou três rodas;
B: Veículos com quatro rodas, que acomodam até oito pessoas e seu peso é de até 3500 kg;
C: Veículos com quatro rodas ou mais e com peso entre 3500 e 6000 kg;
D: Veículos com quatro rodas ou mais e que acomodam mais de oito pessoas; E: Veículos com quatro rodas ou mais e com mais de 6000 kg.


r = int(input("Rodas: "))

kg = float(input("Peso: "))

p = int(input("Passageiros: "))


if r <= 3:

    print("Categoria: A")
   
elif r == 4 and kg <= 3.499 and p < 8:

    print("Categoria: B")

elif r >= 4 and kg >= 3.500 and kg <= 5.999 and p < 8:

    print("C")

elif r >= 4 and p > 8:

    print("Categoria: D")

else:

    print("Categoria: E")

##

### Desafio_3

INSTRUÇÕES DO PROJETO

Faça um código que execute a contagem regressiva de uma bomba,
 informando o número de segundos para explodir. 
Ele deverá mostrar a mensagem “iniciando contagem regressiva”,
 os segundos passados e, no final, a mensagem “BUM!”.

Não é necessário, mas, caso deseje tornar o sistema mais realista para que o tempo realmente passe em segundos, 
você pode usar a função time.sleep() que existe na Python (acesse o link em anexo). 
No entanto, é preciso adicionar uma biblioteca antes de executá-la.


from time import sleep

print('TIME⏳BOMB')

print('💣INICIANDO CONTAGEM REGRESSIVA...')

sleep(2)

print('🤖 📣 5s...')

sleep(2)

print('🤖 📣 4s...')

sleep(2)

print('🤖 📣 3s...')

sleep(2)

print('🤖 📣 2s...')

sleep(2)

print('🤖 📣 1s...')

sleep(2)

print('💣BUM💣💥💥💥💥' *5)

##
##

### Exercícios 
##
  Algoritmo agrupar Lutadores segundo o seu peso:

peso pesado, mais que 73kg;

peso médio, no máximo 73kg;

pena pena, até 57kg


  nome: caractere;

  peso: real;
  
  Início

escreva("Digite o seu nome: ,", nome)

leia(nome)

escreva("Digite o seu peso: ,", peso)

leia(peso)

se(peso <= 57) então

escreva(nome)

escreva("Peso pena")

se não

se(peso < 73) então

escreva(nome)

escreva("Peso médio")

se não

escreva(nome)

escreva("Peso pesado")

Fim se

Fimalgoritmo
  

##
nome = str(input("Digite o nome: "))

peso = float(input("Digite o seu peso: "))

if peso <= 57:

    print(nome)

    print("Peso pena")

elif peso <= 73:

    print(nome)

    print("Peso médio")

else:

    print(nome)

    print("Peso pesado")


    
    






