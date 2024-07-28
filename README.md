# Estudos de CSS Grid

## Introdução
Este projeto tem como objetivo praticar o uso de CSS Grid para layout de páginas web. O CSS Grid é uma poderosa ferramenta para criar layouts bidimensionais complexos e responsivos de maneira simples e eficiente.

## Estrutura do Projeto

### HTML
O HTML deste projeto é composto por uma estrutura básica que inclui a inserção de várias imagens organizadas em um grid.

### CSS
O CSS utiliza a propriedade display: grid para organizar os elementos dentro do body. Cada imagem é posicionada dentro do grid com base em suas propriedades específicas de linha e coluna.

## Explicação das Propriedades CSS Utilizadas

- display: grid: Define que o elemento será um grid container, ativando o uso das propriedades do CSS Grid. Isso permite a organização dos elementos filhos em um layout de grade bidimensional.

- grid-template-columns e grid-template-rows: Define o layout da grade, especificando o número de colunas e linhas, bem como suas proporções. No exemplo, repeat(5, 20%) cria 5 colunas e 5 linhas, cada uma ocupando 20% do espaço total.

- grid-row-start e grid-row-end: Determinam em quais linhas o item do grid deve começar e terminar. Por exemplo, grid-row-start: 1 e grid-row-end: 4 faz com que o item ocupe desde a primeira até a terceira linha (não incluindo a quarta).

- grid-column-start e grid-column-end: Determinam em quais colunas o item do grid deve começar e terminar. Por exemplo, grid-column-start: 1 e grid-column-end: 3 faz com que o item ocupe desde a primeira até a segunda coluna (não incluindo a terceira).

- object-fit: cover: Faz com que a imagem cubra completamente o espaço do grid sem distorcer. A imagem é redimensionada para preencher o container, cortando partes dela, se necessário, para manter a proporção original.

## Conclusão
Este projeto é uma introdução prática ao uso de CSS Grid, mostrando como criar layouts complexos de maneira simples. Continuarei estudando e aprimorando minhas habilidades com CSS Grid para construir interfaces mais eficientes e responsivas.

## Contribuição

Este é um projeto de código aberto, então sinta-se à vontade para contribuir com sugestões, correções de bugs ou até mesmo novas funcionalidades. Todas as contribuições são bem-vindas!

## Licença

Este projeto está licenciado sob a Licença MIT. Para mais detalhes, consulte o arquivo [LICENSE](LICENSE).

---
