// LEARNING HTML //
(1) Creating the boileerplate for my html file
What is a boilerplate ?
The boilerplate for any piece is the basic structure, syntaxor format used for writng a piece of code in any language. Be it CSS, Java, Javascsrsipt, Html, Python or C
(2)Creating elements in Html
What are elements ?
Elements are the components in a pieece of code that make up the code itself, we have different elements in html. Tags are used when creating different types of elements in Html
(3) What are tags in Html ?
Tags are created used the greater than and lesss than operator (<>), they are very useful when creating elemnets in html.
(4) Types of tags in Html
We have the <! DOCTYPE html>, <html>, <head></head>, <meta charset= "UTF-8">, <title></title>, <body>, <p></p>, <h1></h1>, <h2></h2>, <h3></h3>, <h4></h4>, <h5></h5>, <h6></h6>, <strong></strong>, <em></em>, <!--><--!>, </body> </html>
Those are the basic tags used in Html.
(5) Description of each tags
<!DOCTYPE html>
This is the first tag seen in any Html file,it is usually at the heading of any .html extension file. It simply tells the web browser that this is an Html file
<head></head>
This is the head of any Html file, any you all know that when writing a  letter or any other form of writing it will contain a head and a body, it is alsos the same in coding. This is contains two basic things; the title element and the meta charset elements.
<title></title>
This is simply the title or name of your website, or in simpler terms it is whatshows up on the web when someone searches up your wbesite online.
<meta charset= "UFT-8">
This is simply an other additional info about your website, it is stored or contained in this element.
<body></body>
This is the heart and soul of your website, it contains all contents of your website. Without this unigue element your website can't even be called a website. It contains the heading and paragraph and some other features to make your text more stylish and bold.
<p></p>
This is simply the paragraph tag, it houses al your written text and structures them in an organized format.
<h1></h6>
This is the heading tag, it is used to increase the sign of your text and fonts on your wbesite. The bigger the number accompained by the h tag the smaller your font or text size and vice-versa
<strong></strong>
This is an element used to make your text look bold on your website, it is more descriptive than the header tag
<em></em>
This is an element used to make your text on your website italics
Additional tag
<html lang= "en">
This simply species the language used on your website
<!--><--!>
Comments
<!-- EVERYTHING ABOUT CSS>
WHAT ARE SELECTORS?
Selectors simply refer to html elements to which the CSS rules apply, they are the thing s that being selected.
Types of selectors
(1) Universal selector
(2)Type selector
(3)Class selector
(4)ID selector
(5)Grouping selector
(6)Chaining selector

Universal Selector: it is called the universal selector because it refers to every type of element regardless of name or type. It is represented by the asterick sign "*" preceding the openin parenthesis
EXAMPLE:
* {
colour: black;
}

Type Selector: It is simply select that slelects all elements of a given type,the syntax or general name of the element is needed.
EXAMPLE:
div {
colour: purple:
}
p {
colour: black;
}

Class Selector: It is a selector that selects all the elments of the given class, which is an html attribute you place besides it. It really dosen't have to be specific.
EXAMPLE:
<div class="alert-text">Please agree to our terms</div>

.alert-text {
colour: red;
}

ID Selector: it selects every element of the given id, this is also another html attribute.
EXAMPLE:
<div  id="title'>My name is tony</div>

#title {
background-colour: red;
}

Grouping Selector: this selector is used when dealing with two or more elements that share similar style declarations. It is usually denoted using a commaEXAMPLE:
.read {
color: white;
background-color: black;
}

.unread {
color: white;
background-color: black;
}

USING OF THE GROUPING SELECTOR
.read,
.unread {
color: white;
background-color: black;
}

Chaining Selector: this is simply a selector that connests two or more elemnts together with the same or different classes. It is usually denoted with two dots. The first one precedes the first element while the second comes after the before the second.
EXAMPLE:
<div>
<div class="subsection header">Latest posts</div>
<div class="subsection preview">This is where it is</div>

.subsection.header {
color: red;
}
i.e you can also chain or combine more than one selector together

Descendant Cobinator: we have namely four types of combinator, but I'm goin to be talking about the descendant combinator. It is a combinators that selects multiple elements with different selectors. It is usually denoted with a space.
EXAMPLE:
.ancestor .contents {
/* some declarartions */
}
<--!>

<!-- PROPERTIES IN CSS>
(i)Background-color
(ii)Color
(iii)Typography basics and text align
(iv)Image height and width

Each and every element takes a value
<--!>

<!-- METHODS OF ADDING CSS TO HTML>
(i)External CSS
(ii)Internal CSS
(iii)Inline CSS
<--!>
