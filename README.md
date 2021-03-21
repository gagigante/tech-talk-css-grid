## GRID

- Bidimensional
- Organizado em linhas e colunas
- Distribuir elementos neste 'Grid'

## GRID ou FLEXBOX

- GRID: Duas dimensões
- FLEXBOX: Uma dimensão

**Um complementa o trabalho do outro**

## Propriedades

### Container

- display: grid;
- grid-template-columns;
- grid-template-rows;
- grid-gap;
  - grid-row-gap;
  - grid-column-gap;
- grid-template-areas;

- ...alinhamento

### Itens

- grid-column;
  - grid-column-start;
  - grid-column-end;
- grid-row;
  - grid-row-start;
  - grid-row-end;
- grid-area;

- ...alinhamento

## Propriedades de alinhamento:
 
- justify-content;
- align-content;

- justify-items;
- align-items;

- justify-self;
- align-self;

### Justify e Align

- Eixo X: Justify;
- Eixo Y: Align;

### Content

*justify-content* e *align-content* alinha o GRID (*itens*) com relação ao espaço disponível para posicionamento (*container*)

Valores:
- start
- end
- center
- stretch
- space-between
- space-around
- space-evenly

### Items

*justify-items* e *align-items* alinha o conteúdo (*item*) com relação ao espaço disponível na célula do GRID

Valores:
- start
- end
- center
- stretch

### Self

*justify-self* e *align-self* tem o mesmo efeito do item anterior porém aplicado diretamente a um item do GRID
