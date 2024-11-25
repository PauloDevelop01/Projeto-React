# Explicação do Código `Menu`

## Descrição Geral
As mudanças feitas do componente React chamado `Menu` que exibe uma lista de pratos usando o componente `Media` do `reactstrap`.

---

## O que foi feito

1. **Importação de Dependências**  
   - Importado `React` e o hook `useState` para gerenciar o estado.
   - Importado `Media` de `reactstrap` para estruturar a exibição dos pratos.

2. **Estrutura da Lista**  
   - Cada prato possui as seguintes propriedades:  
     - `id`: Identificador único.
     - `name`: Nome do prato.
     - `image`: Caminho para a imagem do prato.
     - `category`: Categoria do prato.
     - `label`: Etiqueta especial.
     - `price`: Preço do prato.
     - `description`: Descrição detalhada do prato.

3. **Mapeamento dos Pratos**  
   - Usou o método `map` para transformar a lista de pratos (`dishes`) em elementos JSX.
   - Cada prato é renderizado dentro de uma estrutura `Media`:
     - Imagem do lado esquerdo (`Media object`).
     - Detalhes do prato (nome e descrição) no corpo (`Media body`).

4. **Retorno do Componente**  
   - O componente retorna uma estrutura de container Bootstrap:
     - Div principal com a classe `container`.
     - Div para organizar a lista com `row`.
     - Lista de pratos encapsulada por `Media list`.

5. **Exportação do Componente**  
   - O componente é exportado como `default` para ser usado em outras partes do projeto.

---

## Estrutura Visual
A lista de pratos será exibida verticalmente, com cada prato ocupando uma linha:
- Imagem do prato no lado esquerdo.
- Nome e descrição alinhados no centro-direita.

---
 ## Por fim 

 foi importado os components para o `App.js` e chamado logo em seguida.

