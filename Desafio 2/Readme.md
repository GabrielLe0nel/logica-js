# Resolução dos desafios do curso lógica de programação: mergulhe em programação com JavaScript (Alura + One)

Praticar a lógica de programação, incluindo conceitos como variáveis e seus tipos diferentes, condicionais e interações com o usuário (alert, prompt). Perguntas retiradas do curso e respostas feitas por mim para praticar.

## Desafios - Respostas

### Exercício 1  do mergulhe em programação JS da ONE. Módulo 2 desafio 9
#### Enunciado: Pergunte ao usuário qual é o dia da semana. Se a resposta for "Sábado" ou "Domingo", mostre "Bom fim de semana!". Caso contrário, mostre "Boa semana!".


```javascript
let dia = prompt("Qual é o dia da semana?");
if (dia == 'Sábado' || dia == 'Domingo') {
    alert('Bom fim de semana!');
} else {
    alert('Boa semana!');
}
```
### Exercício 2 do mergulhe em programação JS da ONE. Módulo 2 desafio 9 
#### Enunciado: Verifique se um número digitado pelo usuário é positivo ou negativo. Mostre um alerta informando.
```javascript
let numero = prompt('Digite um número!');
    if(numero > 0){
        alert('Número positivo!');
    } else{
        alert('Número negativo');
} 
```
### Exercício 3 do mergulhe em programação JS da ONE. Módulo 2 desafio 9 
#### Enunciado: Crie um sistema de pontuação para um jogo. Se a pontuação for maior ou igual a 100, mostre "Parabéns, você venceu!". Caso contrário, mostre "Tente novamente para ganhar.".
```javascript
let pontuacao = prompt('Digite seu ponto.');
if(pontuacao >= 100){
    alert('Parabéns, você venceu!');
} else{
    alert('Tente novamente para ganhar.');
}
```
### Exercício 4 do mergulhe em programação JS da ONE. Módulo 2 desafio 9 
#### Enunciado: Crie uma mensagem que informa o usuário sobre o saldo da conta, usando uma template string para incluir o valor do saldo.
```javascript
let saldoConta = 230; 
alert(`Seu saldo é de R$${saldoConta}.`);
```
### Exercício 5 do mergulhe em programação JS da ONE. Módulo 2 desafio 9 
#### Enunciado: Peça ao usuário para inserir seu nome usando prompt. Em seguida, mostre um alerta de boas-vindas usando esse nome.
```javascript
let nome = prompt('Digite seu nome!');
alert(`Seja bem-vindo(a), ${nome}!`);
```