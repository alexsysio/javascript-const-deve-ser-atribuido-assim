### Variáveis JavaScript devem receber um valor quando são declaradas: const

&nbsp;

### Correto
### const PI = 3.14159265359;
### Incorreto
### const PI;
### PI = 3.14159265359;

&nbsp;

### Quando usar JavaScript const?
### Sempre declare uma variável com const quando souber que O valor não deve ser alterado.
### Use const quando você declarar: 
### Um novo Array
### Um novo Objeto
### Uma nova função
### Um novo RegExp

<a href="https://github.com/user-attachments/assets/39a7168d-b80a-412d-99aa-cbdc216883ff">
  <img width="100%" alt="html-javascript" src="https://github.com/user-attachments/assets/39a7168d-b80a-412d-99aa-cbdc216883ff"/>
</a>

&nbsp;

### Array com const:
### const carros = ["Saab", "Volvo", "BMW"];
### carros[0] = "Toyota";     // ✅ Permitido (modifica o conteúdo)
### carros.push("Audi");      // ✅ Permitido (adiciona elemento)
### carros = ["Fiat", "VW"];  // ❌ ERRO! (reatribuição da variável)

&nbsp;

### Objeto com const:
### javascript
### const pessoa = { nome: "João", idade: 30 };
### pessoa.nome = "Maria";    // ✅ Permitido (modifica propriedade)
### pessoa.cidade = "SP";     // ✅ Permitido (adiciona propriedade)
### pessoa = {};              // ❌ ERRO! (reatribuição da variável)

&nbsp;

### Função com const:
### javascript
### const somar = function(a, b) {
 ###    return a + b;
### };
### somar(2, 3);              // ✅ Funciona normalmente
### somar = function() {};    // ❌ ERRO! (reatribuição)

&nbsp;

### RegExp com const:
### javascript
### const regex = /[a-z]+/;
### regex.test("abc");        // ✅ Funciona normalmente
### regex = /[0-9]+/;         // ❌ ERRO! (reatribuição)

&nbsp;

