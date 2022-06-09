# Boas vindas ao repositório do Projeto Calculadora!

Aqui você vai encontrar os detalhes de como estruturar o desenvolvimento do seu projeto a partir desse repositório, utilizando uma `branch` específica e um _Pull Request_ para colocar seus códigos.

# Sumário

- [Habilidades](#habilidades)
- [Entregáveis](#entregáveis)
  - [O que deverá ser desenvolvido](#o-que-deverá-ser-desenvolvido)

    `Requisitos obrigatórios:`
    - 1 - Encontre o tamanho do Array
    - 2 - Encontre o primeiro e último item do Array
    - 3 - Adicione o ano atual em nossa Array
    - 4 - Ordenação de Array
    - 5 - Imprima todas as posições do Array
    - 6 - Caso condicional 
    - 7 - Loop condicional 
# Habilidades

- Criar códigos que usam estruturas condicionais, como o if/else .
- Manipular arrays (listas);
- Utilizar o comando for ;
- Quebrar grandes problemas em pequenos;
- Utilizar a lógica de programação na resolução de problemas.


# Entregáveis

Para entregar o seu projeto você deverá criar um _Pull Request_ neste repositório.


Todas as funções já estão declaradas no arquivo `script.js`. Você pode criar outras funções para auxiliarem as já existentes. Contudo **Não altere o nome nem conteúdo que estão declarados nas funções que já existem**.

## ⚠️ É importante que seus arquivos não tenham o nome alterado! ⚠️

Lembre-se que você pode e deve consultar qualquer tipo de informação no [Google](https://www.google.com.br/) sempre que precisar!

---

## O que deverá ser desenvolvido

- Você vai complementar funções seguindo os requisitos especificados para o correto comportamento de cada uma delas.
---
## Requisitos do projeto
---
### 👀 Observações importantes:

* Para rodar seu projeto é preciso instalar
a extensão `GoLive` no _VSCode_.

---
### 1 - Encontre o tamanho do Array

Retorne o tamanho exato do array de histórico da nossa calculadora, utilize a variável `historicoDeResultado` já declarada para entregar esse desafio.

**O que será verificado:**
- O número encontrado deve ser exatamente igual à quantidade de posições no array `historicoDeResultado`.

### 2 - Encontre o primeiro e ultimo item do Array

Use a função `firstLastPosition` para complementar sua lógica e encontrar a primeira e última posição do array `historicoDeResultado`.

**O que será verificado:**
- Exemplo: historicoDeResultado = [ `20`, 40, 10, `100` ];
- O resultado da sua função deve trazer um novo Array = [ 20, 100 ];
- Lembre-se de utilizar a variável `requisito2` fazendo uma reatribuição com o seu valor atual. 

### 3 - Adicione o ano atual em nossa Array

Utilizando o método de manipulação `PUSH` você deverá inserir ao final do nosso array o ano atual.

- Dica: já existe uma variável chamada `anoAtual` contendo o valor do ano em que estamos, utilize-a para colocar ao final do array `requisito3` já declarado no corpo da função.

**O que será verificado:**

- Exemplo: historicoDeResultado = [ 55, 80, 18, 22 ];
- O resultado da sua função deve trazer um novo Array = [ 55, 80, 18, 22, `2022` ];
- Lembre-se de utilizar a variável `requisito3` fazendo uma reatribuição com seu o valor atual. 

### 4 - Ordenação de Array

Os valores adicionados no nosso array certamente estão fora de ordem, utilize o método `SORT` para posicionar os itens em ordem crescente e decrescente.

- Para a sua ordenação crescente lembre-se de utilizar a variável `req4crescente` aplicando o método sort da forma correta
- Para a sua ordenação decrescente lembre-se de utilizar a variável `req4decrscente` aplicando o método sort da forma correta

**O que será verificado:**
- Exemplo: historicoDeResultado = [ 55, 80, 18, 22 ];
- O resultado da sua ordenação crescente deve trazer um novo Array = [ 18, 22, 55, 80, `2022` ];
- O resultado da sua ordenação crescente deve trazer um novo Array = [ `2022`, 80, 55, 22, 18 ];
### 5 - Imprima todas as posições do Array

Utilizando um loop, percorra o Array e imprima todas as posições contidas nele.

- Para entregar esse desafio use a função `console.log(sua Resposta)`

**O que será verificado:**

- Se ao abrir o inspecionar do navegador o `console` vai retornar todas as posições contidas no seu array `historicoDeResultado`.

### 6 - Caso condicional 

Descubra se a última posição do array `historicoDeResultado` é maior ou menor que 20.

**O que será verificado:**
- Se a última posição for maior que 20, você deve consolar a String `"maior ou igual a 20"`.
- Se a última posição for menor que 20, você deve consolar a String `"numero é menor que 20"`.
- Se ao abrir o inspecionar do navegador o `console` vai retornar a sua String correta.

### 7 - Loop condicional

Percorrendo o array `historicoDeResultado` verifique os números entre 10 e 20 contidos nele e em seguida adicione ao array `numeros` apenas os valores que atendem a está condição.

- Dica: Utilize o método `PUSH` para inserir os valores encontrados

**O que será verificado:**

- Exemplo: historicoDeResultado = [ 55, 80, `18`, 22, `15` ];
- O array `números` deve conter apenas [ 18, 15 ];---
# Avisos Finais

< Mina Você programa! />

---