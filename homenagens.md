# Homenagens

**Dia das Crianças**

```js
/**
 * 
 * Crianças são como funções puras:
 * - Precisam de parâmetros de entrada
 * - Não dependem do externo
 * - Não provocam efeitos colaterais
 * - Não são tão fáceis de criar
 * - Importantes para um futuro melhor
 *
 */

function fofura(amor, carinho) {
    return (amor + carinho) * 2;
}
```

**Outubro Rosa**

```js
var moment = require('moment');

moment.locale('pt-br');
const OUTUBRO_ROSA = "Outubro";

while (moment().format('MMMM')
    === OUTUBRO_ROSA) {
        console.log(""
            + "Apoio "
            + "às mulheres "
            + "hoje e sempre!");
    
    sync_wait();
}
```

**Dia dos Professores**

```
Assim como o GPS os professores nos guiam para um caminho melhor.
```

**Dia do Profissional de TI**

```prolog
atividade(impressora).
atividade(programação).
atividade(formatação).
atividade(outros).
profissional(carinha).
profissional(mina).
ti(X,Y):-profissional(X),atividade(Y).

/*
 * Mesmo que seu trabalho não envolva
 * consertar impressoras ou
 * formatar computadores,
 * você sempre será o 
 * carinha ou a mina da TI
 */
```

**Natal**

```js
function print(element){
  console.log(element);
}

var altura = 10;
var linha = "";
var fundo = "";
var estrela = "        >>#<<";
var pe = "        #####";

print("O Natal está chegando!\n");
print(estrela);
for (let i = 0; i < altura; i++) {
  linha = "";
  fundo = "";
  for (let j = 0; j < (altura-i); j++) {
    fundo = fundo.concat(' ');
  }
  linha = linha.concat(fundo);
  for (let j = 0; j < (i*2)+ 1; j++) {
    linha = linha.concat('*');
  }
  print(linha)
}
print(pe);
print("\nPor: @trechosdecodigo\n");

/*Saída:
        >>#<<
          *
         ***
        *****
       *******
      *********
     ***********
    *************
   ***************
  *****************
 *******************
        #####

Por: @trechosdecodigo
*/
```