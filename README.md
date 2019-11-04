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

----HTML Computercode

<code>	Defines programming code
<kbd>	Defines keyboard input 
<samp>	Defines computer output
<var>	Defines a variable
<pre>	Defines preformatted text

-----HTML Entities  !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

-----HTML Charset  !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

-----HTML Forms

<input type="text">	    Defines a one-line text input field
<input type="radio">	Defines a radio button (for selecting one of many choices)
<input type="submit">	Defines a submit button (for submitting the form)
<metod="post">          The POST method does not display the submitted form data in the page address field.
<method="get">          When GET is used, the submitted form data will be visible in the page address field
<action>	            Specifies an address (url) where to submit the form (default: the submitting page).
<name>	                Specifies a name used to identify the form (for DOM usage: document.forms.name).
<target>	            Specifies the target of the address in the action attribute (default: _self).

----HTML Form Elements

<form>	    Defines an HTML form for user input
<input>	    Defines an input control
<textarea>	Defines a multiline input control (text area)
<label>	    Defines a label for an <input> element
<fieldset>	Groups related elements in a form
<legend>	Defines a caption for a <fieldset> element
<select>	Defines a drop-down list
<optgroup>	Defines a group of related options in a drop-down list
<option>	Defines an option in a drop-down list
<button>	Defines a clickable button
<datalist>	Specifies a list of pre-defined options for input controls
<output>	Defines the result of a calculation

-----HTML Input Types

<input type="button">
<input type="checkbox">
<input type="color">
<input type="date">
<input type="datetime-local">
<input type="email">
<input type="file">
<input type="hidden">
<input type="image">
<input type="month">
<input type="number">
<input type="password">
<input type="radio">
<input type="range">
<input type="reset">
<input type="search">
<input type="submit">
<input type="tel">
<input type="text">
<input type="time">
<input type="url">
<input type="week">

-----HTML Input Attributes

New Elements in HTML5

Tag	Description
<article>	Defines an article in a document
<aside>	Defines content aside from the page content
<bdi>	Isolates a part of text that might be formatted in a different direction from other text outside it
<details>	Defines additional details that the user can view or hide
<dialog>	Defines a dialog box or window
<figcaption>	Defines a caption for a <figure> element
<figure>	Defines self-contained content
<footer>	Defines a footer for a document or section
<header>	Defines a header for a document or section
<main>	Defines the main content of a document
<mark>	Defines marked/highlighted text
<meter>	Defines a scalar measurement within a known range (a gauge)
<nav>	Defines navigation links
<progress>	Represents the progress of a task
<rp>	Defines what to show in browsers that do not support ruby annotations
<rt>	Defines an explanation/pronunciation of characters (for East Asian typography)
<ruby>	Defines a ruby annotation (for East Asian typography)
<section>	Defines a section in a document
<summary>	Defines a visible heading for a <details> element
<time>	Defines a date/time
<wbr>	Defines a possible line-break

Typical HTML4	        Typical HTML5
<div id="header">	    <header>
<div id="menu">	        <nav>
<div id="content">	    <section>
<div class="article">	<article>
<div id="footer">	    <footer>



-------------------HTML Graphics --------------------------

HTML5 Canvas

The HTML <canvas> element is used to draw graphics, on the fly, via JavaScript.
The <canvas> element is only a container for graphics. You must use JavaScript to actually draw the graphics.
Canvas has several methods for drawing paths, boxes, circles, text, and adding images.

Comparison of Canvas and SVG
The table below shows some important differences between Canvas and SVG:

What is SVG?
SVG stands for Scalable Vector Graphics
SVG is used to define graphics for the Web
SVG is a W3C recommendation

Canvas	SVG
Resolution dependent
No support for event handlers
Poor text rendering capabilities
You can save the resulting image as .png or .jpg
Well suited for graphic-intensive games
Resolution independent
Support for event handlers
Best suited for applications with large rendering areas (Google Maps)
Slow rendering if complex (anything that uses the DOM a lot will be slow)
Not suited for game applications

-------HTML Video

The HTML5 <video> element specifies a standard way to embed a video in a web page.
The controls attribute adds video controls, like play, pause, and volume.
It is a good idea to always include width and height attributes. If height and width are not set, the page might flicker while the video loads.

-----HTML Audio

The HTML5 <audio> element specifies a standard way to embed audio in a web page.
The controls attribute adds audio controls, like play, pause, and volume.

-----HTML Plug-ins

Plug-ins can be added to web pages with the <object> tag or the <embed> tag. 
Plug-ins can be used for many purposes: display maps, scan for viruses, verify your bank id, etc.
The <object> element is supported by all browsers.

The <object> element defines an embedded object within an HTML document.

It is used to embed plug-ins (like Java applets, PDF readers, Flash Players) in web pages.

------HTML Youtube Videos

To play your video on a web page, do the following:

Upload the video to YouTube
Take a note of the video id
Define an <iframe> element in your web page
Let the src attribute point to the video URL
Use the width and height attributes to specify the dimension of the player
Add any other parameters to the URL (see below)              

<iframe width="420" height="315"
    src="https://www.youtube.com/embed/tgbNymZ7vqY">
</iframe>


-------HTML Drag&Drop

First of all: To make an element draggable, set the draggable attribute to true:  <img draggable="true">
In the example above, the ondragstart attribute calls a function, drag(event), that specifies what data to be dragged.
The dataTransfer.setData() method sets the data type and the value of the dragged data:         function drag(ev) {
                                                                                                     ev.dataTransfer.setData("text", ev.target.id);
                                                                                                                 }

The ondragover event specifies where the dragged data can be dropped.

In the example above, the ondrop attribute calls a function, drop(event):

function drop(ev) {
  ev.preventDefault();
  var data = ev.dataTransfer.getData("text");
  ev.target.appendChild(document.getElementById(data));
}

-----HTML Geolocation

coords.latitude	        The latitude as a decimal number (always returned)
coords.longitude	    The longitude as a decimal number (always returned)
coords.accuracy	        The accuracy of position (always returned)
coords.altitude	        The altitude in meters above the mean sea level (returned if available)
coords.altitudeAccuracy	The altitude accuracy of position (returned if available)
coords.heading	        The heading as degrees clockwise from North (returned if available)
coords.speed	        The speed in meters per second (returned if available)
timestamp	            The date/time of the response (returned if available)

------HTML Web Storage

window.localStorage     -   stores data with no expiration date
window.sessionStorage   -   stores data for one session (data is lost when the browser tab is closed)


