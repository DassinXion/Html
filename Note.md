

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

```html
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
</style>

===================Dividing line====================

<!-- Make margin and padding -->
<style>
.injected-text {
    margin-bottom: -25px; 
    text-align: center;}
.box {
    background-color:blue; 
    border-style:solid; 
    border-width: 5px;}
.red-box {
    background-color: red;
    color: #ff;
    padding: 10px 10px 20px 20px;}
.blue-box {
    background-color: blue;
    color: #ff;
    margin: 10px 10px 20px 20px;}
</style>
<h3 class="injected-text">margin</h3>
<div class="box red-box">
	<h5 class="red-box"> padding</h5>
	<h5 class="blue-box"> padding</h5>
</div>

<!--
The **margin** and **padding** sizes ordered with “top, right, bottom. left”. -->

===================Dividing line end====================


```

## Comments

1. Font degrade the first class family as default value, then the  following families.

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

~~But if you want to style some element through the class, you should begin with a point in friont of the elements’ name.~~ <!--INCORRECT-->

```html
<style>
    .p {font-color:red;}
</style>
```

**CORRECT** way out:

Style a customed element with a specific class by using a point ahead;

2. The order of the **class** declarations in the **<style>** section is what is important. The **subsequent** declaration will always take precedence over the **previous**. Nevertheless, **id** attrbute will always take precedence. **inline** styles make sense with a higher priority level. Then, **!important** stays highest priority.
3. Three methods to style color: 
   * Name of color(e.g. blue);
   * Hex code of color(e.g. #00FF00)
   * Abbreviated hex code (e.g. #F00)
   * RGB values
4. Custom CSS variable and fallback value
5. Inherit CSS variable

```html
<style>@media (max-width:350px) { :root{---penguin-size:200px;}}</style>
```

Style elements like meidia query, use an “@” in style commond to define it.



