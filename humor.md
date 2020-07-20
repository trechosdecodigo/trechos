# Humor

**Minhas denpendências**

```gradle
dependencies {
    compile 'cafe:l-or:300.ml'
    compile 'programar:por:9.hrs'
    compile 'fma:brotherhood:ep.9'
    compile 'dormir:por:6.hrs'
}
```

**Sexta-feira 13**

```js
var moment = require('moment');
moment.locale('pt-br');
function diaDoTerror() {
  return moment().format('dddd D');
}

console.log("Hoje é "
  + diaDoTerror() + "!\n"
  + "Cuidado com o "
  + "'Freddy CRUD' "
  + "e com o "
  + "'JSON'!"
  + "\n\n\n");
```

**Ambiguidades**

```js
const AMBIGUIDADE = ""
    + "Para eliminar "
    + "ambiguidades, "
    + "evite dizer "
    + "‘fazer programa’, "
    + "diga "
    + "‘programar’.";

console.log(AMBIGUIDADE);
```

**Falar mal**

```js
alert("Não fale mal da pessoa que fez tal código, ele pode ser seu e você nem lembra que o escreveu.");
```

**Códigos de status de respostas HTTP**

```java
/**
 * Códigos de status de respostas HTTP
 */
public enum ErrosDoCliente {
  C_401(401, "Não autorizado", 
    "Quando você pede algo para a sua mãe e ela não deixa."),

  C_402(402, "Pagamento necessário",
    "Quando você baixa um app mas ele é pago."),

  C_403(403, "Proibido",
    "Quando você é de menor e quer ir para a balada."),

  C_404(404, "Não encontrado",
    "Quando você abre sua carteira procurando dinheiro."),

  C_405(405, "Método não permitido",
    "Quando você faz gambiarras."),

  C_406(406, "Não aceito",
    "Quando você tem preconceitos."),

  C_407(407, "Autenticação de Proxy Necessária",
    "Quando você tenta acessar o Facebook no trabalho."),

  C_408(408, "Tempo de solicitação esgotado",
    "Quando você desiste de esperar pela(o) crush."),

  C_409(409, "Conflito",
    "Quando seu colega edita uma classe sua."),

  C_410(410, "Eliminado",
    "Quando você passa dessa para melhor.");

  int CODIGO;
  String MENSAGEM;
  String DETALHE;

  ErrosDoCliente(int codigo,
    String quandoFalam,
    String oQueEuPenso) {
    CODIGO = codigo;
    MENSAGEM = quandoFalam;
    DETALHE = oQueEuPenso;
  }
}
```



**Na minha máquina funciona**

```js
/*
 * Aquela frase que 
 * a gente tenta evitar
 */
function aquelaFrase() {
    return atob(
        "TmEgbWluaGEgbeFxdWluYSBmdW5jaW9uYQ=="
    );
}
console.log("\n");
console.log(aquelaFrase());
console.log("\n");

//Saída: Na minha máquina funciona

```

**Código reprovado**

```pas
program CodeReview;

var
  resultado : String;
  
begin
  write('Resultado: ');
  read(resultado);

  if(resultado = 'reprovado') then
    write('Quem nunca teve o código reprovado que atire a primeira tecla.')    
  else write(':D');

end.
```