# alura-aulas iniciais

let nome = Lua;
let idade = 43; 
let numeroDeVendas = 50;
let saldoDisponivel = 1000;
let idadeMinima = 18;
let maiorDeIdade = 'Você pode tirar habilitação';
let menorDeIdade = 'Você não pode tirar habilitação';
let mensagemDeErro = 'Erro! Preencha todos os campos.';
alert (mensagemDeErro);
let nome = prompt ('Qual o seu nome?');
let idade = prompt ('Qual a sua idade ?');

if (idade >= idadeMinima) {
    alert (maiorDeIdade);
} 
if (idade < idadeMinima) {
    alert (menorDeIdade);
}
