# box-shadow-task
• What are the new tags added in HTML5?
•	<article> tag: The <article> tag is one of the new sectioning element in HTML5. The HTML <article> tag is used to represent an article. More specifically, the content within the <article> tag is independent of the other content of the site (even though it can be related).
•	<aside> tag: The <aside> tag is used to describe the main object of the web page in a shorter way like a highlighter. It basically identifies the content that is related to the primary content of the web page but does not constitute the main intent of the primary page. The <aside> tag contains mainly author information, links, related content, and so on.
•	<audio> tag: The <audio> tag is used to insert an audio into an HTML webpage.
•	<canvas> tag: The <canvas> tag in HTML is used to draw graphics on a web page using JavaScript. It can be used to draw paths, boxes, texts, gradients, and add images. By default, it does not contain borders and text.
•	<command> tag: The <command> tag define a command button, invoke as per user action. The <command> tag button is used in a special type of operation. The <command> tag is supported only by Internet Explorer.
•	<datalist> tag: The <datalist> tag is used to provide autocomplete feature in the HTML files. It can be used with an input tag so that users can easily fill the data in the forms using select the data.
•	<details> tag: The <details> tag is used for the content/information which is initially hidden but could be displayed if the user wishes to see it. This tag is used to create an interactive widget that the user can open or close. The content of the details tag is visible when opening the set attributes. The <summary> tag is used with the <detail>s tag for specifying visible heading.
•	<embed> tag:  The <embed> tag in HTML is used for embedding external applications which are generally multimedia content like audio or video into an HTML document. It is used as a container for embedding plug-ins such as flash animations. This tag is a new tag in HTML 5, and it requires only starting tag.
•	<figure> tag: The <figure> tag in HTML is used to add self-contained content like illustrations, diagrams, photos, or codes listing in a document. It is related to the main flow, but it can be used in any position of a document and the figure goes with the flow of the document and if remove it then it should not affect the flow of the document. This tag is new in HTML5.
•	<footer> tag: The <footer> tag in HTML is used to define a footer of HTML document. This section contains the footer information (author information, copyright information, carriers, etc). The footer tag is used within the body tag. The <footer> tag is new in the HTML5. The footer elements require a start tag as well as an end tag.
•	<header> tag: The <header> tag contains information related to the title and heading of the related content. The <header> element is intended to usually contain the section’s heading (an h1-h6 element or an <hgroup> element), but this is not required.The <header> element can also be used to wrap a section’s table of contents, a search form, or any relevant logos. The <header> tag is a new tag in HTML5 and it requires a starting tag as well as an end tag. There can be several <header> elements in one document. A <header> tag cannot be placed within a <footer>, <address> or another <header> element.
•	<hgroup> tag: The <hgroup> tag in HTML stands for heading group and is used to group the heading elements. The <hgroup> tag in HTML is used to wrap one or more heading elements from <h1> to <h6>, such as the headings and sub-headings. The <hgroup> tag requires the starting tag as well as ending tag.
•	<keygen> tag: The <keygen> tag in HTML is used to specify a key-pair generator field in a form. The purpose of the<keygen> element is to provide a secure way to authenticate users. When a form is submitted then two keys are generated, private key and public key. The private key is stored locally, and the public key is sent to the server. The public key is used to generate a client certificate to authenticate a user for the future.
•	<mark> tag: The <mark> tag in HTML is used to define the marked text. It is used to highlight the part of the text in a paragraph. The <mark> tag is new in HTML5.
•	<meter> tag: It is used to define the scale for measurement in a well-defined range and also supports a fractional value. It is also known as a gauge. It is used in Disk use, relevance query result, etc.
•	<nav> tag: The <nav> tag is used for declaring the navigational section in HTML documents. Websites typically have sections dedicated to navigational links, which enables users to navigate the site. These links can be placed inside a nav tag. In other words, the nav element represents a section of the page whose purpose is to provide navigational links, either in the current document or to another document. The links in the nav element may point to other web pages or to different sections of the same webpage. It is a semantic element. Common examples of the nav elements are menus, tables, contents, and indexes.
•	<output> tag: The <output> tag in HTML is used to represent the result of a calculation performed by the client-side script such as JavaScript. The <output> tag is a new tag in HTML5, and it requires a starting and ends tag.
•	<progress> tag: It is used to represent the progress of a task. It is also defined how much work is done and how much is left to download a thing. It is not used to represent the disk space or relevant query.
•	<ruby> tag: The <ruby> tag in HTML is used to specify the ruby annotation which is a small text, attached with the main text to specify the meaning of the main text. This kind of annotation is used in Japanese publications.
•	<section> tag: The <section> tag defines the section of documents such as chapters, headers, footers, or any other sections. The section tag divides the content into sections and subsections. The section tag is used when requirements of two headers or footers or any other section of documents are needed. The <section> tag grouped the generic block of related contents. The main advantage of the section tag is, it is a semantic element, which describes its meaning to both browser and developer.
•	<time> tag: The <time> tag is used to display the human-readable date/time. It can also be used to encode dates and times in a machine-readable form. The main advantage for users is that they can offer to add birthday reminders or scheduled events in their calendar’s and search engines can produce smarter search results.
•	<wbr> tag: The <wbr> tag in HTML stands for word break opportunity and is used to define the position within the text which is treated as a line break by the browser. It is mostly used when the used word is too long and there are chances that the browser may break lines at the wrong place for fitting the text.
•	<video> tag: The <video> tag is used to embed video content in a document, such as a movie clip or other video streams.


• How to embed audio and video in a webpage?
Attributes of <audio> tag
Attribute	Value	Description

controls	Controls	It displays audio control. 
loop	Loop	It will start the audio again when it is finished. 
muted	Muted	When the page is loaded audio will be automatically muted. 
preload	auto metadata
none	It specifies how the author thinks the audio will be loaded when the page is ready. 
src	URL	It specifies the URL of the audio file. 
Attributes of <video> tag
Attribute	Value	Description
autoplay	autoplay	When the page is loaded. It specifies to play video as soon as possible. 
controls	controls	It displays video control such as play, pause, and stop.
loop	loop	It will start the video again when it is finished. 
muted	muted	When the page is loaded video will be automatically muted. 
poster	URL	It specifies an image will be shown until video play. 
preload	auto
metadata
none	It specifies how the author thinks the video will be loaded when the page is ready. 
src	URL	It specifies the URL of the audio file. 
width	pixels	It specifies the width of the video area. The default value of width is ‘auto’.
height	pixels	It specifies the height of the video area. The default value of height is ‘auto’.



 • Semantic element in HTML5?
Many web sites contain HTML code like: <div id="nav"> <div class="header"> <div id="footer"> to indicate navigation, header, and footer.
In HTML there are some semantic elements that can be used to define different parts of a web page:  
•	<article>
•	<aside>
•	<details>
•	<figcaption>
•	<figure>
•	<footer>
•	<header>
•	<main>
•	<mark>
•	<nav>
•	<section>
•	<summary>
•	<time>
 

 • Canvas and SVG tags
SVG	Canvas
Vector based (composed of shapes)	Raster based (composed of pixel)
SVG has better scalability. So it can be printed with high quality at any resolution.	Canvas has poor scalability. Hence it is not suitable for printing on higher resolution.
SVG gives better performance with smaller number of objects or larger surface.	Canvas gives better performance with smaller surface or larger number of objects.
SVG can be modified through script and CSS.	Canvas can be modified through script only.
Multiple graphical elements, which become the part of the page’s DOM tree.	Single element similar to <img> in behavior. Canvas diagram can be saved to PNG or JPG format.




