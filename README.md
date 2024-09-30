# front-end-bootcamp-practices
## Some notes about CSS properties
1. Box-sizing: content-box(default)

--> change to 'border-box' so that width and height of an element include border + padding+content 

2. ul : has padding left by default 

--> inspect we gonna see ::market pseudo element

3. hover effect: disappear -> appear
option 1: set max-width/height:0; overflow:hidden -> max-width/height:100vh
option 2: opacity:1 -> opacity:0
option 3: display:none -> other type of display
option 4: transform:scale(0);visibility:hidden -> transform:scale(1);visibility:visible
4. y-axis: top to bottom; x-axis: left to right
5. banner text styling
6. Measurements
- px: used majorly for gap, spacing
7. iframe + a tag+ text-container for hover effect
8. position relative + position absolute -> need to give outer container width and height so that the absolute positioned element stays inside the container.
9. top+left+transform:translate -> centralised an element inside a container
## Responsive CSS
1. @ Media tag: similar to adding another internal CSS which is only in use in some specific conditions. Since Media tag is declared at the bottom of html file, it has higher priority 
2. Two type of responsive styling: mobile-first( use min-width as a condition) or desktop-first( use max-width as a condition)

## Some notes on Flex box and Grid
1. Flex box

- flex-direction: row -> width of block element changes from full width to 0 -> set width of each element to width:100%, all elements will have equal width.
- flex-direction:  column -> width of block element will be full width of its parents if we dont declare the width for each.
- properties: 
--> other flex-direction : row-reverse, column-reverse
--> justify-content: follow the flex-direction, one of very commonly used : spaced-evenly
--> align-content: baseline -> all texts are on the same line ( inside child element, outside child element)
- Content is the most important  in html, therefor it wont be resized -> need to use flex-wrap property

2. Grid






