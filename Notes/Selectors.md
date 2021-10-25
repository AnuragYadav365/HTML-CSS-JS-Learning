## Anatomy of a CSS Rule

Collection of CSS Rules is called StyleSheet.

- Selector: Identifier of element
- CSS Declaration: Properties of every elements

> CSS Declaration consists: Property and Value

### Types Of Selector

- Element Selector

p{
    color: blue;
}

- Class Selector: Tag must attribute class (for example here class="blue")

.blue {
    color: blue;
}

- Id Selector: 
1. Tag must attribute id (for example here id="name")
2. Must be unique for every element to apply CSS.

#name {
    color: blue;
}

#### [Grouping Selector]

Example :

div, .blue {
    color: blue;
}

### Element with class selector

- Every p that has class="big".
p.big {
    font-size: 20px;
}

Example:
<p class="big">This text will be affected</p>
<div class="big">This text will not be affected</div>

### Child/Direct selector

- Read from right to left.
- Every p that is a direct child of article.

article > p{
    color: blue;
}

### Descendant selector

- Every p that is inside(at any level) of article
article p{
    color: blue;
}


<hr>

### Pseudo-Class Selector

Examples:
- :link
- :visited
- :hover
- :active
- :nth-child(...)