# Include HTML Using Javascript

## Prototyping Web Pages Quickly By Components
I found a new way to quickly prototype my web pages and creating the site viusal components. 
That is create different section as different files: header.html, footer.html, body.html and etc.<p/>

All this without a web server using something like server side includes of:<br/>
PHP: include 'filename';<br/>
Apache: <!--#include virtual="/cgi-bin/counter.pl" --> </p>

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
inc_header.html
inc_footer.html
inc_headerconfig.html
inc_navigation.html
inc_pagetop.html<p/>

## Scripts and CSS
The site is using bootstrap4, font-awsome and the support javascript and css

 

