# Prototyping Web Pages Quikly With Javascript Includes

## Include HTML Files Using Javascript
I found a new way to quickly prototype my web pages and creating the __site viusal components__. 
That is create different section of the web page using different files. Example: header.html, footer.html, body.html and etc.<p/>

All this without a web server, server side includes like that of:<br/>
PHP: include './incl/inc_somepage.html';<br/>
Apache: include virtual="/incl/inc_somepage.html"


Use something like this:<br/>
&lt;div&lt;w3-include-html="inc_header.html"&gt;&lt;/div&gt;
<br/>
&lt;div&lt;w3-include-html="inc_body_index.html"&gt;&lt;/div&gt;

## www.w3schools.com "How to Include HTML" javascript
The includes are created using www.w3schools.com includeHTML.js. You can download it from: https://www.w3schools.com/howto/howto_html_include.asp.

## I am demoing this approach using:
index.html - The root page for the web page with links to three other pages:<br/>
starthere.html - The start here page.<br/>
demo.html - The demo page.<br/>
about.html - The about page.<p/>

## The include files for the pages:
inc_body_index.html - Include for about index page<br/>
inc_body_starthere.html - Include for start here page<br/>
inc_body_about.html - Include for about page<br/>
inc_body_demo.html - Include for demo page<br/>

## The site has these reusable include files:
inc_header.html<br/>
inc_footer.html<br/>
inc_headerconfig.html<br/>
inc_navigation.html<br/>
inc_pagetop.html<p/>

## Scripts and CSS
The site is using bootstrap4, font-awsome and the support javascript and css

