CSS Basics: Cascading Style Sheet(CSS) is used to set the style in web pages that contain HTML elements, here we will see in how many ways we can add CSS for our HTML, there three different ways to do so one by one we will see those procedure.

External CSS: External CSS contains a separate CSS file with a .css extension which contains only style property with the help of tag attributes.

selector{
property1: value1;
property2: value2;
}
Include external CSS file: The external CSS file is linked to the HTML document using a link tag.

<link rel="stylesheet" type="text/css" href="/style.css" />
Internal CSS or Embedded: CSS is embedded within the HTML file using a style HTML tag when a single HTML document must be styled uniquely.

<style type="text/css">
div { color: #444;}
</style>
Inline CSS: It contains CSS properties in the body section specified within HTML tags using the style attribute.

<tag style="property: value"> </tag>
Clearfix: It is used to clear floats to select or keep control of your margins and padding.

.clearfix::after {
 content: "";
 clear: both;
 display: block; 
}
Selectors: CSS selectors are used to find or selecting the HTML elements you want to style. These are categorized as follows:


Basic Selectors	Description	Syntax
Universal	Selects all elements on the pages. ‘*’ symbol is used to denote the selector as a universal selector.	*{property:value;}
Type	Type selector or tag name/element selector selects an HTML tag/element in your document. It selects all elements of the given type within a document.	p {
CSS declarations;
}
Id	Selects an element based on the value of its unique id attribute(One id only applied to one element). An ID selector begins with a # rather than a dot character.	#id {css declarations; }
Class	Selects all elements in the document that have the given class attribute. It class selector starts with a dot (.) character.	.class {
css declarations;
}
Attribute	Selects all elements that have a specified attribute. Elements grouped based on some attribute value can be styled using an attribute selector.	a[attribute=value] {
property: value;
}
Combinators	Combinators are complex selectors consisting of more than one selectors having some relationship between them. These are the font-family General Sibling selector, Adjacent sibling selector, child selector, Descendant selector.	selector1 selector2/ selector 1+selector2 / selector 1> selector 2 {property: value;}
Pseudo	A Pseudo class in CSS is used to define the special state of an element to add an effect to an existing element based on its states. For ex. change of state on hover, click, focus, when a link is visited, etc.	selector: pseudo-class{
property: value;
}
