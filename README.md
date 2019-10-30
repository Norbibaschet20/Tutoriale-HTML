# Tutoriale-HTML

-------Attributes
alt	       Specifies an alternative text for an image, when the image cannot be displayed
disabled   Specifies that an input element should be disabled
href       Specifies the URL (web address) for a link
id         Specifies a unique id for an element
src        Specifies the URL (web address) for an image
style      Specifies an inline CSS style for an element
title      Specifies extra information about an element (displayed as a tool tip)


-------Formatting
<b>	    Defines bold text
<em>	Defines emphasized text 
<i>	    Defines italic text
<small>	Defines smaller text
<strong>Defines important text
<sub>	Defines subscripted text
<sup>	Defines superscripted text
<ins>	Defines inserted text
<del>	Defines deleted text
<mark>	Defines marked/highlighted text

-------HTML Quotation and Citation Elements
       
<abbr>	        Defines an abbreviation or acronym
<address>	    Defines contact information for the author/owner of a document
<bdo>	        Defines the text direction
<blockquote>	Defines a section that is quoted from another source
<cite>	        Defines the title of a work
<q>	            Defines a short inline quotation

------HTML Comment Tags

<!-- This is a comment -->  Comments are not displayed by the browser, but they can help document your HTML source code.

------Colors

 style="background-color:DodgerBlue;">Hello World   You can set the background color
 style="color:Tomato;">Hello World                  You can set the color of text
 style="border:2px solid Tomato;">Hello World       You can set the color of borders
 
 style="background-color:rgb(255, 99, 71)
 style="background-color:#ff6347                    Same color using HSL HEX RGB
 style="background-color:hsl(9, 100%, 64%)

-------HTML Styles - CSS

Use the HTML style attribute for inline styling
Use the HTML <style> element to define internal CSS
Use the HTML <link> element to refer to an external CSS file
Use the HTML <head> element to store <style> and <link> elements
Use the CSS color property for text colors
Use the CSS font-family property for text fonts
Use the CSS font-size property for text sizes
Use the CSS border property for borders
Use the CSS padding property for space inside the border
Use the CSS margin property for space outside the border

-------HTML Links

<a>	        Defines a hyperlink
Use the href attribute to define the link address
Use the target attribute to define where to open the linked document
Use the <img> element (inside <a>) to use an image as a link
Use the id attribute (id="value") to define bookmarks in a page
Use the href attribute (href="#value") to link to the bookmark
The title attribute specifies extra information about an element.

--------HTML Images

<img>	    Defines an image
<map>	    Defines an image-map
<area>	    Defines a clickable area inside an image-map
<picture>	Defines a container for multiple image resources
Use the HTML src attribute to define the URL of the image
Use the HTML alt attribute to define an alternate text for an image, if it cannot be displayed
Use the HTML width and height attributes to define the size of the image
Use the CSS float property to let the image float

-------HTML Tabels

<table>	    Defines a table
<th>	    Defines a header cell in a table
<tr>	    Defines a row in a table
<td>	    Defines a cell in a table
<caption>	Defines a table caption
<colgroup>	Specifies a group of one or more columns in a table for formatting
<col>	    Specifies column properties for each column within a <colgroup> element

-------HTML Lists

<ul>	Defines an unordered list
<ol>	Defines an ordered list
<li>	Defines a list item
<dl>	Defines a description list
<dt>	Defines a term in a description list
<dd>	Describes the term in a description list
Use the CSS list-style-type property to define the list item marker
Use the HTML type attribute to define the numbering type

------HTML Blocks

<div>	Defines a section in a document (block-level)
<span>	Defines a section in a document (inline)

-----HTML Classes
class="abc" --->  .abc {...}


-----HTML Id

id="abc" --->  #abc {...}

-----HTML Iframes

<iframe>	Defines an inline frame

----HTML Javascript

<script>	Defines a client-side script
<noscript>	Defines an alternate content for users that do not support client-side scripts

-----HTML Filepath

<img src="picture.jpg">	picture.jpg is located in the same folder as the current page
<img src="images/picture.jpg">	picture.jpg is located in the images folder in the current folder
<img src="/images/picture.jpg">	picture.jpg is located in the images folder at the root of the current web
<img src="../picture.jpg">	picture.jpg is located in the folder one level up from the current folder 

-----HTML Head

<head>	Defines information about the document
<title>	Defines the title of a document
<base>	Defines a default address or a default target for all links on a page
<link>	Defines the relationship between a document and an external resource
<meta>	Defines metadata about an HTML document
<script>	Defines a client-side script
<style>	Defines style information for a document
<meta name="viewport" content="width=device-width, initial-scale=1.0">    The viewport is the user's visible area of a web page. It varies with the device, and will be smaller on a mobile phone than on a computer screen.

-----HTML Layouts

HTML Layout Techniques
There are five different ways to create multicolumn layouts. Each way has its pros and cons:

HTML tables (not recommended)
CSS float property
CSS flexbox
CSS framework
CSS grid


<header> - Defines a header for a document or a section
<nav> - Defines a container for navigation links
<section> - Defines a section in a document
<article> - Defines an independent self-contained article
<aside> - Defines content aside from the content (like a sidebar)
<footer> - Defines a footer for a document or a section
<details> - Defines additional details
<summary> - Defines a heading for the <details> element

-----HTML Responsive

<meta name="viewport" content="width=device-width, initial-scale=1.0">  When making responsive web pages, add the following <meta> element in all your web pages
If the max-width property is set to 100%, the image will scale down if it has to, but never scale up to be larger than its original size
font-size:10vw   That way the text size will follow the size of the browser window

