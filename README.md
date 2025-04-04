# 7 Days of Code

O "7 Days of Code" é um desafio de programação criado pela Alura, onde durante sete dias, você recebe um desafio diário que deve ser resolvido utilizando uma linguagem e tecnologia de sua escolha. O objetivo é aprimorar habilidades e adquirir novos conhecimentos em desenvolvimento de software, explorando diferentes áreas de programação. Estou participando deste desafio para me desafiar, expandir meu aprendizado e melhorar minhas habilidades na área de tecnologia.

## Módulo do Desafio: Lógica com JavaScript

O módulo "Lógica com JavaScript", ministrado pela instrutora Rafa Ballerini. Neste módulo, o objetivo é praticar e reforçar conceitos de lógica de programação, utilizando a linguagem JavaScript para resolver problemas práticos.

---

## ⚡ Dia 1

### Desafio Proposto:
No primeiro dia do desafio, o objetivo foi comparar duas variáveis, verificando se elas têm o mesmo valor, mesmo que seus tipos sejam diferentes. Em seguida, também deveria ser verificado se elas possuem o mesmo tipo de dado.

### O que foi feito:
A solução foi implementar uma função que compara duas variáveis. O código verifica primeiro se as variáveis possuem o mesmo valor (considerando tipos diferentes, como números e strings que podem ser iguais, como `1` e `'1'`). Em seguida, é realizada uma segunda verificação para saber se as variáveis possuem o mesmo tipo.

A função principal (`compararVariaveis`) recebe dois objetos contendo o nome e o valor das variáveis e retorna uma mensagem descrevendo o resultado das comparações.

### 💻 Tecnologias Usadas:
- **JavaScript**: A linguagem escolhida para este desafio. Utilizei JavaScript para implementar a lógica de comparação de variáveis.

### Partes Importantes da Programação:

1. **Comparação de Valores**:
   A comparação de valores é feita utilizando o operador `==`, que permite comparar valores de tipos diferentes, como números e strings.

   ```js
   function compararValores(valor1, valor2) {
       return valor1 == valor2;
   }
   ```

2. **Comparação de Tipos**:
   Para comparar o tipo das variáveis, é utilizado o operador `===`, que verifica tanto o valor quanto o tipo, garantindo que as variáveis sejam do mesmo tipo.

   ```js
   function compararTipos(tipo1, tipo2) {
       return tipo1 === tipo2;
   }
   ```

3. **Uso de JSDoc para Melhor Legibilidade e Manutenção**:
   Para garantir que o código seja mais fácil de entender e de manter, utilizei o JSDoc para documentar a função `compararVariaveis`. O uso do JSDoc facilita a leitura e a manutenção, além de permitir uma melhor autocompletação e insights em editores de código.

   ```js
   /**
    * Compara duas variáveis, verificando se elas têm o mesmo valor e se possuem o mesmo tipo.
    * 
    * @param {Object} objeto1 O primeiro objeto contendo o nome e o valor da variável.
    * @param {string} objeto1.nome O nome da primeira variável.
    * @param {any} objeto1.valor O valor da primeira variável.
    * @param {Object} objeto2 O segundo objeto contendo o nome e o valor da variável.
    * @param {string} objeto2.nome O nome da segunda variável.
    * @param {any} objeto2.valor O valor da segunda variável.
    * 
    * @returns {string} A mensagem que descreve a comparação entre as variáveis.
    */
   function compararVariaveis(objeto1, objeto2) {
       let textoResultado = `Resultado da comparação das variáveis:\n[ ${objeto1.nome} ] e [ ${objeto2.nome} ]\n`;

       let temMesmoValor = compararValores(objeto1.valor, objeto2.valor);
       textoResultado += `\n${temMesmoValor ? "" : "não "}tem o mesmo valor`;

       if (temMesmoValor) {
           let temMesmoTipo = compararTipos(objeto1.valor, objeto2.valor);
           textoResultado += temMesmoTipo ? " e mesmo tipo" : ", mas tipos diferentes";
       }

       return textoResultado;
   }
   ```

---

## ⚡ Dia 2

**(Adicionar informações sobre o desafio do Dia 2 assim que for completado)**

---

## Próximo Módulo

**(Adicionar informações sobre o próximo módulo, conforme você avançar nos desafios)**

## 📁 Acesso ao projeto

Você pode [baixar o arquivo zip]("coloque_o_link_aqui").

## 🛠️ Abrir e rodar o projeto

Após baixar o projeto, você pode abrir com o Visual Studio Code para acessa-lo e modificar o código. Para isso, na tela inicial clique em:

- **Open Folder** (ou alguma opção similar)
- Procure o local onde o projeto está e o selecione (Caso o projeto seja baixado via zip, é necessário extraí-lo antes de procurá-lo)
- Por fim clique em OK

Para  abrir, basta clicar duas vezes no arquivo **index.html** que ele será aberto no seu navegador, e você poderá testar suas funcionalidades

# Time

| [<img loading="lazy" src="https://avatars.githubusercontent.com/u/113655013?v=4" width=115><br><sub>Christian Rui</sub>](https://github.com/Christian-Rui)
| :---: |
