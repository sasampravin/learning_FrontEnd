# $${\color{gold}CSS \space GRID }$$

> ## ${\color{red}to \space Parant \space or \space Grid \space container \space properties}$

### ${\color{green}display : grid}$

This the mandatory property we have to write in the parant tag with this we are creating grid container.

#### ${\color{yellow}grid-template-columns}$
- Here we specify howmany columns and width of items we want.
- EX:grid-template-columns : 200px 130px 520px;
- EX:grid-template-columns : 2fr 5fr 1fr 3fr;
- each value is one column
- if we give auto as grid value it will occupy whole area.
- repeate(no.of-columns, value-px)
#### ${\color{yellow}grid-template-rows}$
- Here we specify howmany rows and height of items we want.
- EX:grid-template-rows : 250px 180px 420px; 
- EX:grid-template-columns : 1fr 3fr 2fr 6fr;
- each value is one row
- if we give auto as grid value it will occupy whole area.
- repeate(no.of-rows, value-px)
#### ${\color{yellow}grid-template}$
- The grid-template CSS property is a shorthand that allows you to define grid columns, rows, and areas in a CSS grid container with one declaration.
#### ${\color{yellow}grid-template-ateas}$
- child1 chile1 child2 these are the name of the grid area of the child
-  EX: <tag>text</tag> here grid area is text area name
#### ${\color{yellow}grid-row-gap}$
- It will give gap between rows
#### ${\color{yellow}grid-column-gap}$
- It will give gap between columns
#### ${\color{yellow}grid-gap}$
- It give space between grid-rows and grid-column
#### ${\color{yellow}justify-items}$
- Horizontally align and apply to grid items
- default occupy stretch value
#### ${\color{yellow}align-items}$
- Vertically align and apply to grid items
- default occupy stretch value

 ## ${\color{red}to \space Child \space or \space Grid \space items \space Properties}$

#### ${\color{yellow}grid-column-start}$
- starting point of the grid column lines
#### ${\color{yellow}grid-column-end}$
- ending point of the grid column lines
#### ${\color{yellow}grid-column}$
- shart hand notation for both grid-column-start and grid-column-end of the grid lines
#### ${\color{yellow}grid-row-start}$
- starting point of the grid row lines
#### ${\color{yellow}grid-row-end}$
- ending point of the grid row lines
#### ${\color{yellow}grid-row}$
- shart hand notation for both grid-row-start and grid-row-end of the grid lines
#### ${\color{yellow}grid-area}$
- specifies the location and the size of a grid item in a grid layout by setting the value of grid-row-start , grid-column-start , grid-row-end and grid-column-end in one declaration.
#### ${\color{yellow}justify-self}$
- Horizontally justify and apply to the specific child grid item only
#### ${\color{yellow}align-self}$
- Vertical align and apply to the specific child grid item only

