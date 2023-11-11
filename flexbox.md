# Flexbox

## What is flexbox
![What is flexbox?](./assests/flexbox.png)

## Flexbox terminology
![flexbox terminology](./assests/flexbox-terminology.png)

## Flexbox cheatsheet
![flexbox cheatsheet](./assests/flexbox-cheatsheet.png)

- ```flex-grow```:
  - This property determines how much a flex item should grow relative to the rest of the items in the flex container.
  - If all items have flex-grow set to 1, they will share the available space equally.
  - Higher values mean a greater share of the available space.

- ```flex-shrink```:
  - Conversely, flex-shrink determines how much a flex item should shrink if the container is too small.
  - A value of 0 means the item won't shrink. A higher value means it can shrink more.
  - This helps to prevent items from becoming too small when there's not enough space.

- ```flex-basis```:
  - This property sets the initial size of a flex item before any available space is distributed.
  - It can be a length (like pixels or percentage) or the keyword auto, which means the size is determined by the item's content.
  - It establishes the base size of the item in the ```main axis``` **(width)**.
