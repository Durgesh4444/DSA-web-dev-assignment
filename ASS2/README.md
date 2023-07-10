## Q.1 Whats Box Model in CSS ?
> Ans-The CSS box model is a container that contains multiple properties including borders, margins, padding, and the content itself. It is used to create the design and layout of web pages. The web browser renders every element as a rectangular box according to the CSS box model. Margin, Border and Padding are three CSS properties which are part of it.


## Q.2 What are the Different Types of Selectors in CSS & what are the advantages of them?  
> Ans- Selectors in CSS are used to select a particular element for the purpose of adding some style to it. different types of  selectors are 
>1 Element selector - Is used to select a particular element from the HTML file, advantage of this selector is suppose if we have more than one1 h1 or other tag we can select them at a time. 

>2 class selector - if  we want to style more than one > h1  or other tag  differently then we have to add class or id attribute in it then we can style them differently 
>Ex.  .tittle{color: #000}

>3 Id selector Ex.  #tittle{ color: #fff}

>4 Universal selector  - if we want to add some style in whole page then we use the universal selector Ex.  *{margin:0; padding:0}

>5 Attribute selector  - attribute selector is used to select all the elements that have the specified attribute and applies the CSS property to that attribute. For example the selector [class] will select all the elements with the style attribute.
Ex. [class]{color:red}

>6 Pseudo-class selector - A Pseudo class in CSS is used to define the special state of an element. It can be combined with a CSS selector to add an effect to existing elements based on their states. For Example, changing the style of an element when the user hovers over it, or when a link is visited. All of these can be done using Pseudo Classes in CSS.
Ex. selector: pseudo-class{  property: value;}

>7  Pseudo-element selector - A CSS pseudo-element is a keyword added to a selector that lets you style a specific part of the selected elements. For Example, Styling the first letter or line of an element,
Ex. selector::pseudo-element {property: value;}

## Q.3 What is VW/VH ?
>Ans - VW/VH are the units of measurement used in CSS to set height, width etc.
>VW - Relative to 1% of the width of the viewport
>VH - Relative to 1% of the height of the viewport
>PX - It define the font-size in term of pixels (96px = 1in)

## Q.4 What is difference between Inline, Inline Block and block ?
>Ans - Inline- when we use display inline property to an element will take that much of space  only which is required but we can not set height and width of that element

>Inline-Block -  when we use display inline-block property to an element will take that much of space  only which is required and we can  set height and width of that element

>Block -when we apply display block property to an element will take whole space of  that particular line and we can not set another element beside of that element

## Q.5 How is Border-box different from Content Box?
>Ans- Border box and content box are the styling properties of box-sizing 
>Content-box is the default behavior of box sizing , in this case if we have two container parent container and child container , width of both the container is same and suppose we add a border of 10px to child container , that  container overflows outside parent container . 

>And  in case we set the box-sizing of the child container to border-box, that child container sticks to the boundary of the parent container and does not overflow outside of the parent container. 



## Q.6 What’s z-index and How does it Function ? 
>Ans - z-index sets the order of overlapping elements, elements with higher z-index cover/ overlap  the element with lower z-index. But one of them should be positioned other than static.


## Q.7 What’s Grid & Flex and difference between them? 
>Ans -The CSS Grid Layout is a two-dimensional grid-based layout system with rows and columns. It is useful in creating more complex and organized layouts.
> The CSS Flexbox is a one-dimensional layout. It is useful in allocating and aligning the space among items in a grid container. It works with various kinds of display devices and screen sizes. Flex layout makes it easier to design and build responsive web pages without using many float and position properties in the CSS code.

## Q.8 Difference between absolute and relative and sticky and fixed position explain with example. 
>Ans - Position Absolute - with the help of this property we can set the position of child container/element with respect to first non static parent element. 

>Position relative - with the help of this property we can set the position of perticular element with respect to its original position. 

>Position sticky - with the help of this property we can fixed the position of  particular element after user scroll page with certain amount.

>Position fixed- with the help of this property we can fixed the position of particular element anywhere you want.

## Q.9 Build Periodic Table as shown in the below image (10 Marks)
Project link -  Periodic Table

## Q.10 Build Responsive Layout both desktop and mobile and Tablet, see below image for reference ? 
Ans- Responsive Layout
