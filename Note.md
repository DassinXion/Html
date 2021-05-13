

# HTML



```html
<h1> Hello World </h1>	
<p>
    This is a paragraph.
</p>

<!--
This is a comment
-->

<main>A tag in HTML for easier to read and help with Search Engine Optimization</main>

<a href= "baidu.com" Target= "blank">A BAD search engine</a>

<a href= "#footer" > Jump to Bottom</a>
<footer id= "footer">Copy Right All Reserved</footer>

<ul>
    <li>Unordered list item1</li>
    <li> " item2</li>
    ...
</ul>

<ol>
    <li>Ordered list item1</li>
    ...
</ol>

<form action="link.com">
    <input type= "text" required placeholder= "Default Text">
    <button type="submit">
        Submit
    </button>
    <label> <input id="option1" type="radio" name= "Group1">Option1 </label> 
    <label> <input id="option2" type="radio" name= "Group1">Option2 </label>
</form>
```

# CSS

```css
<h1 style= "color:blue;"> H1 text with color blue</h1>

<style>
h1 {color:blue;}
</style>

<style>
.blue-text{color: blue;}
</style>

<h2 calss= "blue-text"> This is a class styled H2 title with blue</h2>

<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type='text/css'>
<style>
h2{font-family: Lobster, Monospace}
```

## Comments

Font degrade the first class family as default value, then the  following families.

Set an element an ID is simple:

```html
<p id=“Thefirstparagraph”> These people are always happy.</p>
```

And in the style element, you can define the style to the id elements with a “#”.

```html
<style>
    #Thefirstparagraph{font-color:blue; font-size:16px; background-color: gray;}
</style>
```

But if you want to style some element through the class, you should begin with a point in friont of the elements’ name.

```html
<style>
    .p {font-color:red;}
</style>
```

