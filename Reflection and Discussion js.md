#  page(1-10)
how java script make your website more interactive 

1- ACCESS CONTENT
You can use JavaScript to select any
element, attribute, or text from an
HTML page. For example:
• Select the text inside all of the <hl> 
 elements on a page
• Select any elements that have a c 1 ass attribute with a value of note
• Find out what was entered into a text input whose id attribute has a value of ema i 1
  
  2- ) MODIFY CONTENT You can use JavaScript to add
elements, attributes, and text to the
page, or remove them. For example:
• Add a paragraph of text after the
first <hl> element
• Change the value of c 1 ass
attributes to trigger new CSS rules
for those elements
• Change the size or position of an
<i mg> element 
  
  3 -) PROGRAM RULES You can specify a set of steps for the browser to follow (like a recipe), which allows it to access or change the content of a page. For example:
• A gallery script could check which image a user clicked on and display a larger version of that image.• A mortgage calculator could collectvalues from a form, perform a calculation, and display repayments.An animation could check the dimensions of the browser window and move an image to the bottom of the viewable area (also known as the viewport).

4- ) REACT TO EVENTS You can specify that a script should run when a specific event has occurred. For example, it could be run when:
•A button is pressed
•A link is clicked (or tapped) on
•A cursor hovers over an element
•Information is added to a form
•An interval of time has passed
•A web page has finished loading

## page 

EXAMPLES OF JAVASCRIPT
IN THE BROWSER
Being able to change the content of an HTML page while it is loaded in
the browser is very powerful. The examples below rely on the ability to:
1- Access the content of the page
2- Modify the content of the page
3- Program rules or instructions the browser can follow
4- React to events triggered by the user or browser
example ;- 
RELOAD PART OF PAGE
 
You might not want to force visitors to reload the
content of an entire web page, particularly if you
only need to refresh a small portion of a page.
Just reloading a section of the page can make a
site feel like it is faster to load and more like an
application.
React: Script triggered when user clicks on link
Access: The link that they clicked on
Program: load the new content that was requested
from that link
Access: Find the element to replace in the page
Modify: Replace that content with the new content
Some early examples in this book do not work with Internet Explorer 8
and earlier (but alternative code samples that work in IE8 are available to
download from http:// j avascri pt book. com). We explain techniques
for dealing with older browsers in later chapters.
Each version of a web browser adds new features.
Often these new features make tasks easier, or are
considered better, than using older techniques.
But, website visitors do not always keep up with
the latest browser releases, so website developers
cannot always rely upon the latest technologies.
As you will see, there are many inconsistencies
between browsers that affect JavaScript developers.
jQuery will help you deal with cross-browser
inconsistencies (it is one of the major reasons why
jQuery rapidly gained popularity amongst web
developers). But, before you learn jQuery, it helps to
know what it is helping you to achieve.
8 INTRODUCTION
To make JavaScript easier to learn, the first few
chapters use some features of JavaScript that are
not supported in IE8. But:
• You will learn how to deal with IE8 and older
browsers in later chapters (because we know that
many clients expect sites to work in IE8).
It just requires knowledge of some extra code
or requires you to be aware of some additional
issues.
• Online, you will find alternatives available for
each example that does not work in IE8.
But please check the comments in those code
samples to make sure you know about the about
issues involved in using them.

*A script is a series of instructions that a
computer can follow to achieve a goal.
You could compare scripts to any of the following: 




