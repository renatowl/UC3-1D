# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 


## Conteúdo Técnico
Escreva aqui os conteúdos aprendidos.

## Switch case

O termo "switch case" refere-se a uma estrutura de controle utilizada em programação para selecionar um bloco de código a ser executado com base no valor de uma expressão.

const bairro = prompt("Qual é o seu bairro?")

```switch (bairro) {
  case "arruda":
    console.log("entrega gratis")
    break;
  case "beberibe":
    console.log("taxa de R$5,99")
    break;
  case "peixinhos":
    console.log("taxa de R$9,99")
    break;
}
```
## Var

A palavra var é uma palavra-chave usada em várias linguagens de programação para declarar variáveis. O significado e o comportamento de var podem variar dependendo da linguagem.

## Let

Em JavaScript, let foi introduzido no ECMAScript 6 (ES6) e serve como uma alternativa moderna ao var. A principal diferença entre let e var é o escopo e o comportamento relacionado ao hoisting
```
let a = 20
let b = 80
let somar = a + b

console.log(somar)
```

## Const

A palavra-chave const é usada em várias linguagens de programação para declarar variáveis cujo valor não pode ser alterado após a inicialização. Dependendo da linguagem, o comportamento de const pode variar, mas a ideia principal é garantir que o valor da variável permaneça constante.
```
const  nome = "Renato"
const sobrenome = "pereira"
const fullname = nome + " " + sobrenome

console.log ("Meu nome é:" + fullname)
```
## If else

A estrutura if-else é uma das construções básicas de controle de fluxo em muitas linguagens de programação. Ela permite que você execute diferentes blocos de código com base em condições específicas. 
```
const combo = prompt ("Deseja comprar novo combo de cerveja?")
if(combo == "sim") {
 console.log(`Parabéns ${nome}, você comprou uma skol!`)
}
   console.log("Muito obrigado(a), volte sempre!")
```
## Array

Um array (ou vetor) é uma estrutura de dados fundamental usada em programação para armazenar um conjunto de elementos do mesmo tipo. Esses elementos são armazenados em posições contíguas na memória e podem ser acessados através de índices.

```
//Array 

const livros = ["Javascript Assertivo", "ECMAScript 6","MongoDB", "Whendell","Swewnson","Nicous"]

console.log(livros[2]);

const consulta = livros.indexOf("MongoDB")

console.log(consulta)
console.log(livros.pop(6));
console.log(livros.push("Vasco da gama"));
console.log(livros.sort())
```

## Atividades desenvolvidas
Escreva aqui as atividades desenvolvidas em sala e para casa. Você pode detelhar a atividade e usar links das atividades do codepen e vídeos desenvolvidos em sala. 

# Array
https://codepen.io/Renatowl/pen/wvLpQYw

# Switch Case
https://codepen.io/Renatowl/pen/GRbOxZz
