# Resolução dos desafios do curso lógica de programação: mergulhe em programação com JavaScript (Alura + One)

Feito para a prática de lógica de programação, incluindo conceitos como variáveis e seus tipos diferentes, loops (while), condicionais e interações com o usuário (alert, prompt). Perguntas retiradas do curso e respostas feitas por mim para praticar.

## Desafios - Respostas

### Exercício 1  do mergulhe em programação JS da ONE. Módulo 3 desafio 7
#### Enunciado: Crie um contador que comece em 1 e vá até 10 usando um loop while. Mostre cada número.

```javascript
let contador = 1;

while (contador <= 10) {
    alert(contador);
    contador ++;
}
```
### Exercício 2  do mergulhe em programação JS da ONE. Módulo 3 desafio 7 
#### Enunciado: Crie um contador que começa em 10 e vá até 0 usando um loop while. Mostre cada número.
```javascript
let contador = 10;

while(contador >= 0){
    alert(contador);
    contador--;
}
```
### Exercício 3  do mergulhe em programação JS da ONE. Módulo 3 desafio 7
#### Enunciado: Crie um programa de contagem regressiva. Peça um número e conte deste número até 0, usando um loop while no console do navegador.
```javascript
let numeroFornecido = prompt('Digite o número: ');
while (numeroFornecido >=0) {
    console.log(numeroFornecido);
    numeroFornecido--;
}
```
### Exercício 4  do mergulhe em programação JS da ONE. Módulo 3 desafio 7
#### Enunciado: Crie um programa de contagem progressiva. Peça um número e conte de 0 até esse número, usando um loop while no console do navegador.
```javascript
let progressao = prompt('Digite o número');
let contador = 0;

while(progressao >= contador){
    console.log(contador);
    contador++;
```