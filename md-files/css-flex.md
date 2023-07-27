# $${\color{gold}CSS Flex block}$$

> ## ${\color{red}to \space parant \space tag}$

#### ${\color{green}display : flex}$

This the mandatory property we have to write in the parant tag, by default it will arange the items in row wise.

#### ${\color{yellow}1. flex-direction :}$

- row ---> It will adjest the all flex items in the row direction from left to right
- row-reverse ---> It will adjest the flex items in the row reverse direction from right to left
- column ---> It will adjest the all flex items in the column direction from top to buttom
- Column-reverse ---> It will adjest the flex items in the column reverse direction from buttom to top

#### ${\color{yellow}2. flex-wrap :}$

- nowrap ---> It is the default value to wrap the flexible itema nothing but nowrap.
- wrap ---> It is the value that which adjest the flexble items if it is necessary(gives value to the items properties).
- wrap-reverse ---> It specify the that the flexible item will wrap if it is necessary(gives value to the items properties) in the reverse order.

#### ${\color{yellow}3. flex-flow :}$

- flex-direction flex-wrap ---> It is a shart hand notation, this is the combination of the two properies(flex-direction,flex-wrap) that will adjest the flexible item accordingly.

#### ${\color{yellow}4. justify-content :}$

```
justify contant is used to adjest the flex items in the main axis.
if flex direction row mani-axis --> x cross-axis --> y
if flex direction column mani-axis --> y cross-axis --> x
```

- flex-start ---> flex items will be started from the starting point of that row/column
- flex-end ---> flex items will be started from the end point of that row/column

* center ---> flex items will be kept in center.

- space-between ---> It will give the remaining space between the flex items.

* space-around ---> It will give the remaining space in the left & right side of the flex items.
* space-evenly ---> It will give the remaining space in the left & right side of the flex items evenly(equally).

#### ${\color{yellow}5. align-items :}$

- flex-start
- flex-end

* center

- baseline

* stretch

#### ${\color{yellow}6. align-content :}$

<!--
```
align-items is used to adjest the flex(child) items in the cross axis.
if flex direction row mani-axis => x cross-axis => y
if flex direction column mani-axis => y cross-axis => x
```
-->

- flex-start ---> It will place the flex items at the starting point in the vertical direction
- flex-end ---> It will place the flex items at the end in the vertical direction

* center ---> ---> It will place the flex items at center the vertical direction
* space-between ---> It will give the space between flex items in the vertical direction

- space-around ---> It will give the space between flex items in the vertical direction

> ## ${\color{red}to \space child \space tag}$

#### ${\color{yellow}order : integer}$

According to order number child items are displayed ,default value is zero for all.

#### ${\color{yellow}flex-grow : number}$

It will divide the space and apply to the flex-grow number

#### ${\color{yellow}flex-shrink : number}$

It will reduce the space of the shrink item accordingly.

#### ${\color{yellow}flex-basis : }$

- length

* auto

#### ${\color{yellow}flex :}$

- flex-grow flex-shrink flex-basis

#### ${\color{yellow}align-self :}$(for paricular flex item)

- auto
- flex-start ---> It will keep the flex item at the starting point
- flex-end ---> It will keep the flex item at the end point
- center ---> It will keep the flex item at the center point
- baseline ---> Specifying the initial length of the flex item
- stretch ---> It will make the flex item narrow or wider.
