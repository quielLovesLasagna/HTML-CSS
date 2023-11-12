# CSS Grid

## What is grid

![grid](./assests/grid.png)

## Grid teminology

![grid terminology](./assests/basic-grid-terminology.png)

![more grid terminology](./assests/more-grid-terminology.png)

## Grid cheatsheet

![grid cheatsheet](./assests/grid-cheatsheet.png)

- ```justify-cotent``` and ```align-content``` are used to align tracks inside of the container **_(ONLY APPLIES IF CONTAINER IS LARGER THAN THE GRID ITSELF)_**.
  - justify is for the ```row-axis``` (horizontal)
  - align is for the ```column-axis``` (vertical)

EXAMPLE:
```css
justify-content: center;
align-content: center;
```
![for contents](./assests/cotents.png)

#

- ```justify-items``` and ```align-items``` are used to align items inside their cell.
  - justify is for the ```row-axis``` (horizontal)
  - align is for the ```column-axis``` (vertical)
  - Note: you can always override these declaration using ```justify-self``` and ```align-self``` properties which is used for **SINGLE GRID ITEMS** (use it for individual elements).
 
EXAMPLE:

```css
/* CENTER THE GRID */
justify-content: center;
align-content: center;

/* CENTER THE ITEMS (IN THEIR CELL) */
justify-items: center;
align-items: center;
```
![items](./assests/items.png)















