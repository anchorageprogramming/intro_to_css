Introduction to CSS
=============

Exercise Sheet for the introduction to css class  
[Slides](https://docs.google.com/presentation/d/1iVZpjwzjffHvBWZvY-LYMkR8M8shJnGQzY7oQTCrkhM/edit?usp=sharing)

## Explore how CSS can effect your page
1. Navigate to the [CSS Zen Garden website](http://www.csszengarden.com).
1. On the right hand side of the page, select [Make 'em Proud](http://www.csszengarden.com/?cssfile=/212/212.css). Notice how the list of designs is now on the left side of the page! CSS did that.     
1. On the left hand side of the page, select [A Robot Named Jimmy](http://www.csszengarden.com/?cssfile=/215/215.css). Notice how the list of designs is at the bottom of the page.    
1. Play around with the different themes and notice how the colors, headings, and elements rearrange themselves on the page.  

## Create or use an existing html page
### Use our example HTML page
1. On the right hand side of this screen, you'll see a button that says **Download ZIP**. Click it!  
1. Unzip the folder and open the index.html file in a text editor like Notepad.  
1. Open the style.css file in a text editor as well.  

*or*  

### Use the page you created last time
1. Wherever you saved the index.html file you worked on last time, open it in a text editor.  
1. Create a file titled style.css in the same folder.  

## Add a link to the file in the head of the index file.  
Why didn't we do this for you? Because it's fun to do it yourself!  
**In your index.html file look for the `<head>` element. It looks like this:**  
```html
<head>
  <title>Hello World</title>
</head>
```
**Insert the following snippet underneath the `<title>` element:**  
```html
<link rel="stylesheet" type="text/css" href="style.css">  
```
This tells the browser "When you display this page, please follow the rules in this file for styling."  

## Change the colors for your main elements
In your **style.css** file:  
**Change the background color for the body element.**  
```css
body {
  background-color: green;
}
```
**Change the background color for a paragraph.**   
```css
p {
  background-color: orange;
}
```
**Change the text color of an element.  Example:**  
```css
p {
  background-color: orange;
  color: white;  
}
```

## Add selectors to your html elements 
In your **index.html** file:  
**Add a class to several html elements. Here's an example that adds two classes:**   
```html
<p class="tanya">How was your day?</p>
<p class="adele">It was fine thanks.</p>
<p class="tanya">Was it really fine?</p>
```
**Add an id to an html element. Here's an example:**  
```html
<p id="jess">Hey ya'll, what are you talking about?</p>
```

## Change the colors for your classes and ids
In your **style.css** file:  
**Add a selector for a class and change the text color. A class selector is indicated by the `.` in front of the word. Here's an example:**  
```css
.tanya {
  color: green;
  background-color: silver;
}

.adele {
  color: white;
  background-color: maroon
}
```
**Add a selector for an id and change the text color. An id selector is indicated by the `#` in front of the word. Here's an example:**  
```css
#jess {
  color: red;
}  
```
## Next steps
* Play around with other css properties. See a list of them at the [Mozilla Developer's Network](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference?redirectlocale=en-US&redirectslug=CSS%2FCSS_Reference).
* Sign up for Code academy and take the web Fundamentals class!  
[Code Academy](http://www.codecademy.com/tracks/web) 
