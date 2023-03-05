# Guia de Markdown

Use **asteriscos duplos** ou __underlines duplas__ para negrito.

Use  *asteriscos simples* ou _underlines simples_ para itálico.

Use "~" duplos para ~~riscar textos~~.

Também podemos **_misturar_** elementos, como o negrito e o itálico.


# Use "#" no começo de uma frase (com espaço) para montar um título.

## Use "##" no começo de uma frase para montar um título de nível 2.

### Use "###" no começo de uma frase para montar um título de nível 3.

Use três vezes o "-" para montar uma linha.

---

Ou use três vezes o "*" para montar uma linha.

***

## Listas

Podemos montar uma lista numerada sem nos preocuparmos com a ordem dos números, como no exemplo abaixo:

1. Item 1 da lista, com número 1 no código;
3. Item 2 da lista, com número 3 no código;
7. Item 3 da lista, com número 7 no código.

Para montar subitens, basta adicionar um novo item com 3 espaços no começo, como no exemplo abaixo montado a partir do exemplo anterior:

1. Item 1 da lista, com número 1 no código;
3. Item 2 da lista, com número 3 no código;
   1. Subitem 1 do item 2, com número 1 no código;
   4. Subitem 2 do item 2, com número 2 no código.
7. Item 3 da lista, com número 7 no código.


Da mesma forma podemos montar uma lista demarcada, porém com asteriscos ou traços no começo:

* Item 1 da lista;
* Item 2 da lista;
   * Subitem 1 do item 2;
   * Subitem 2 do item 2.
* Item 3 da lista.

***

Para montar uma lista de tarefas, usamos "- [ ]" no começo dos itens. E para marcar como concluído, adicionamos um "x" entre os colchetes.

- [x] Tarefa 1
- [ ] Tarefa 2
   - [x] Tarefa 2.1
   - [ ] Tarefa 2.2
- [ ] Tarefa 3

***

## Anexos

Para adicionar uma imagem, iniciamos a linha com: `![ ]( )`, onde dentro dos colchetes deve ir uma descrição da imagem e dentro dos parênteses a url da imagem, como no exemplo abaixo:

![Imagem logo da conta](https://github.com/vinis-moraes/Guia-de-Markdown/blob/main/81641780.png)

A descrição da imagem será usada caso não seja possível acessar o arquivo, como no exemplo abaixo:

![Imagem logo da conta]()

Para criar hiperlinks, a fórmula é muito parecida com a das imagens, com uma pequena diferença: nós removeremos o ponto de exclamação. Veja o exemplo abaixo: 

[Minha página do GitHub](https://github.com/vinis-moraes)

***

## Tabelas

Para criar uma tabela, usaremos o pipe(também conhecido como barra de pé) "|" e os traços "-". Separaremos as colunas usando os pipes e as linhas usando os traços, veja o exemplo e depois o código:

Coluna 1 | Coluna 2 | Coluna 3
---|---|---
L1, C1 | L1, C2 | L1, C3
L2, C1 | L2, C2 | L3, C3

![Captura de tela com o código da tabela](https://github.com/vinis-moraes/Guia-de-Markdown/blob/main/Captura-de-tela-1.png)


## Comandos

Para montar um comando com texto monoespaçado, usamos crase "`" antes e depois da frase,

`O resultado deve ser parecido com esse`