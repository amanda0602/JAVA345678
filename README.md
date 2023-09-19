# JAVA345678

console.log("Operações Aritiméticas");

console.log(2+2);
console.log(10 + 8 * 2);
console.log((10 + 8) * 2);

console.log("ano" + 2020);
console.log("2" + "2");
 11 changes: 11 additions & 0 deletions11  
4-conversaoDetipos.js
@@ -0,0 +1,11 @@
console.log("Conversão de Tipos");

console.log("ano" + 2020);
console.log("2" + "2");
console.log(parseInt("2") + parseInt("2"));

console.log("7" / "2");
console.log("Ricardo" / "2"); //Not a Number

console.log(6.5);
console.log(6,5);
 14 changes: 14 additions & 0 deletions14  
5-atribuicaoVariaveis.js
@@ -0,0 +1,14 @@
console.log("Trabalhando com atribuição de variáveis");
const idade = 29;
const primeiroNome = "Ricardo";
const sobrenome = "Bugan";

//console.log(nome + " " + sobrenome)
console.log(primeiroNome, sobrenome)
console.log(`Meu nome é ${primeiroNome} ${sobrenome}`);

let contador = 0
contador = contador +1
const nomeCompleto = primeiroNome + sobrenome;
console.log(nomeCompleto);
nomeCompleto =2;



onsole.log("Trabalhando com atribuição de variáveis");
const idade = 29;

const primeiroNome = "Ricardo";
const sobrenome = "Bugan";

//console.log(nome + " " + sobrenome)
console.log(primeiroNome, sobrenome)
console.log(primeiroNome, sobrenome);
console.log(`Meu nome é ${primeiroNome} ${sobrenome}`);

let contador = 0
contador = contador +1
let contador = 0;
contador = contador +1;

const nomeCompleto = primeiroNome + sobrenome;
console.log(nomeCompleto);
nomeCompleto =2;

let idade; //declarando variável
idade = 26; //atribuindo valor
idade = idade+1;
console.log(idade);

 23 changes: 23 additions & 0 deletions23  
6-listas.js
@@ -0,0 +1,23 @@
console.log(`Trabalhando com listas`);
// const salvador = `Salvador`;
// const saoPaulo = `São Paulo`;
// const rioDeJaneiro = `Rio de Janeiro`;

let new = 2;

const listaDeDestinos = new Array(
    `Salvador`,
    `São Paulo`,
    `Rio de Janeiro`
);

listaDeDestinos.push(`Curitiba`) // adicionando um item na lista
console.log("Destinos possíveis:");
//console.log(salvador, saoPaulo, rioDeJaneiro)
console.log(listaDeDestinos);

listaDeDestinos.splice(1,1);
console.log(listaDeDestinos);

@@ -3,8 +3,6 @@ console.log(`Trabalhando com listas`);
// const saoPaulo = `São Paulo`;
// const rioDeJaneiro = `Rio de Janeiro`;

let new = 2;

const listaDeDestinos = new Array(
    `Salvador`,
    `São Paulo`,
 46 changes: 46 additions & 0 deletions46  
7-condicionais.js
@@ -0,0 +1,46 @@
console.log(`Trabalhando com condicionais`);
const listaDeDestinos = new Array(
    `Salvador`,
    `São Paulo`,
    `Rio de Janeiro`
);

const idadeComprador = 18;
const estaAcompanhada = false;
const temPassagemComprada = true;

console.log("Destinos possíveis:");
console.log(listaDeDestinos);

// if (idadeComprador >= 18) {
//     console.log("Comprador maior de idade");
//     listaDeDestinos.splice(1, 1); //removendo item
// } else if (estaAcompanhada == true) {
//     console.log("Comprador está acompanhado");
//     listaDeDestinos.splice(1, 1); //removendo item
// } else {
//     console.log("Não é maior de Idade e não posso vender");
// }

if (idadeComprador >= 18 || estaAcompanhada == true) {
    console.log("Boa Viagem!!");
    listaDeDestinos.splice(2, 1); //removendo item
} else {
    console.log("Não é maior de Idade e não posso vender");
}

console.log("Embarque: \n\n")
if(idadeComprador >= 18 && temPassagemComprada){
    console.log("Boa viagem");
}else{
    console.log("Você não pode embarcar");
}


console.log(listaDeDestinos);

// console.log(idadeComprador > 18);
// console.log(idadeComprador < 18);
// console.log(idadeComprador <= 18);
// console.log(idadeComprador >= 18);
// console.log(idadeComprador == 18);
