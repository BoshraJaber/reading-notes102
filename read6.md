# Introducing CSS

CSS is combined of rules that help you with controling how the content of an element should appear.
### First: Understanding CSS: Thinking Inside the Box
The key to understanding how CSS works is to imagine that there is an invisible **box** around every **HTML element**.
This will help us see the page that we want to create inside of our head before starting to write the code!
CSS rules help us control the box and its content!
### Second: Blocks & Inline elements
* Block level elements look like they start on a new line..
* Inline elements flow within the text and do not start on a new line. 

### CSS Associates Style rues with HTML elements
In other words, we can add CSS rules to our HTML elements in order to cuztimize them the way we desire!
 Here is an example of a CSS rule applied to a HTML element:
![A example CSS rule](https://puzzleweb.ru/en/images/css/1_1.png)


And Here is a practical example:
![html element](https://www.tutorialchip.com/wp-content/uploads/2011/01/Re-Defining-HTML-Tags.jpg)
### Linking CSS with HTML:
To do so:
1. Go to your HTML code
2. Between the **head** opening and closing tag
3. Write the following line:

![an example](https://help.globalscape.com/help/cuteftp9/images/DB_NewDocumentTemplate_link.gif)

### Using Internal CSS:
In case you don't to create a new CSS file, you can still apply CSS rules inside your HTML code, and here is how:
![an example](https://csharpcorner-mindcrackerinc.netdna-ssl.com/UploadFile/219d4d/basics-of-css-part-1/Images/paragraph%20color.png)

### CSS Selectors:
Remember: *Rules* are made of *selectors*
[Here is a link that can give you a good idea of the most common selectors in CSS](https://www.w3schools.com/cssref/css_selectors.asp) 

# Color
Let's add some colors to our page so it would look alive in just a few lines!
You can specify any color in CSS in one of three ways:
1. RBG Values
2. Hex Codes
3. Color Names

## Background Color:
``` body {
background-color: rgb(200,200,200);}
h1 {
background-color: DarkCyan;}
h2 {
background-color: #ee3e80;}
p {
background-color: white;} 
```

Other features you can use:
* Contrast
* Opacity
* HSL Colors ( Hue, Saturation,Lightness )

