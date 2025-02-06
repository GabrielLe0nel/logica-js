# Resolução dos desafios do curso lógica de programação: mergulhe em programação com JavaScript (Alura + One)

Feito para a prática de lógica de programação, incluindo conceitos como variáveis e seus tipos diferentes, loops (while), condicionais e interações com o usuário (alert, prompt). Perguntas retiradas do curso e respostas feitas por mim para praticar.

## Desafios - Respostas

### Exercício do mergulhe em programação JS da ONE. Módulo 4 desafio 7 (operador ternário)
#### Transforme a seguinte condição if-else em operador ternária:
```javascript

let palavraPessoa = "";

if(quantidadePessoas == 1){
    palavraPessoa = "pessoa";
}else{
    palavraPessoa = "pessoas"
}
```

Resposta:
```javascript
let palavraPessoa = quantidadePessoas == 1 ? 'pessoa' : 'pessoas';
```