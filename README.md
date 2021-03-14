# PREWORK-2
How to build your first web page. 

This is the first bit of code that I put together. 
I was tempted to make some revisions after the Perscholas boot camp 
but decided to leave it as is to be reminded later of where I started.  


These are the directions for 

#Building your first webpage. 

This is a rugh layout to give you an idea but any of the toppics below you can research on your own to find out 
more about each. This is ment to be used as a simple guide. I have added notes taken from the asignment to help somewhat but may not be all the information you will need. 

To do this you will need a text editor. I suggest Visual Studio Code.

Some fundimentals. 

  HTML Boilerplate - breakdown
1. First we have to tell our file that it will contain HTML. We do this by creating the following tag at the very top of the document: <!DOCTYPE html>
Note: There is no closing tag. This is all you need at the top of your document.
2. Next we will need a pair of html tags: <html></html>
IMPORTANT: You need to write ALL of your html code in between these html tags.
3. Inside of your html tags you will need head tags: <head></head>
Not to be confused with header tags. This is where you add your title tags: <title></title> for the title of your site as well as where you’ll be linking stylesheets and scripts (More on these later).
4. And finally you have your body tags: <body></body>
This is where the main content of your document will live. This is the section that will be visible on the browser and where you will insert all of your html elements.

  **I have added code when setting up this readme but it will not show when I save the changes. My apoligies. **
    
      <!DOCTYPE html>
      <html>
      <head>
          <title>Your title here!</>
        </head>
          <body>
           <!--Content of the page goes in the body-->
         </body>
         </html>
  
  **You can now render your web page in the browser and see your title. 
  to do this...
  On your HTML where you just made your Boikerplate page 
  -right click in that window to bring up the drop
  down box
  -click: Open with Live Server. 
  This will open you application in a browser window and you should now see you title.**
  
    Using HTML Tags: Comments
● When you are creating your HTML you may want to leave some notes or comments for yourself or other developers
● This is the opening tag of a comment <!-- and this is the closing tag -->
● Comments can be seen by anyone looking at the source code, but they will not be rendered by the
browser
  Example
<!-- This is a comment -->  

 
   Using HTML tags: anchor tag
● To add a link to a text or image on a html page, Anchor tag is used. ○ <a href = #> www.google.com </a>
● Anchor tags have href attribute that specifies the hypertext reference which points to where the text should be linked.
● To make a text look like a link, enclose in <a> tag.
● If you don’t have a link yet, use # as a placeholder
  
 Using HTML tags: HTML Lists
● Two types of lists can be created in HTML
○ Ordered list using <ol> </ol> tag
○ Unordered lists <ul> </ul> tag

 Using HTML tags: HTML Lists - unordered list
● Unordered lists <ul> </ul> tag ○ <li> list item </li>
        
it looks like (you can look up an example being these are not going to show in the readme
  <ol>
  <li>Stuff 1</li>
  <li>Stuff 2</li>
  <li>Stuff 3</li>
  </ol>
  it renders as this
    1. Stuff 1
    2. Stuff 2
    3. Stuff 3

 Using HTML tags: special characters
● For special characters to show up on a web page like an Accent mark; Less than sign; or Copyright sign. ● Example:
○ &lt; is used for <
○ &gt; is used for >
○ &amp; is used for &
○ &nbsp; is used for a space
○ &copy; is used for a ©
 
   Review of HTML elements
● Header Element - <h1></h1>
○ Used for titles. There are 6 types of header tags (h1,
h2, h3, h4, h5, h6)
○ The higher the number in the tag the smaller the
text will be

● Paragraph Element - <p></p>
○ Used to display text

● <b> bold </b> Make text between tags bold

● <i> italic </i> Make text between tags italic

● Unordered List Element - <ul></ul>
○ Used to create a bulleted list
○ Each list item should be wrapped in <li></li> tags

● Ordered List Element - <ol></ol>
○ Used to create a numbered list
○ Each list item should be wrapped in <li></li> tags

 ● Anchor Element - <a></a>
○ Anchor tags are used to create links
○ The link will go inside of the opening <a> tag
○ Text is inserted in between the tags to let users
know where the link is going
  <a href="url"> link name </a> Create a link to another page or website  
  
● Image Element - <img/>
○ Used to insert images to a webpage
○ Images can be linked using an image url or an
image file
○ Notice that there is no closing tag. This tag is
considered self closing 
  or
  <img src="filename.jpg">Show an image
  (will need closing tag for this one)
  
● <b> bold </b> Make text between tags bold

● <i> italic </i> Make text between tags italic

● <br/> is for break. Here this is self closing and is used to give some space or a 'break' between elements. 

● <div></div> div tags work as containers for other elements. 
  
  **you can look up HTML cheat sheets and save your favorite for reference**

The Requirements for this assignment:

This was for this assignment but of course if you are doing this on your own you can add in your own personal own ideas. 

  
 Day 1 Tell us about yourself
1. Create an HTML webpage about yourself. This page must include a minimum of following elements
1.1. Your name in the title (to appear on the browser tab)
1.2. A heading of level 2 containing your name
1.3. A heading of level 3 containing a welcome message
1.4. A paragraph, with a few sentences about yourself
1.5. An image, to represent you
1.6. Link the the image or some text on the page, to an external website
1.7. A list (ordered or unordered). You can use this to tell us about your favorite projects, things you find interesting etc


We will add new things each day to build out your first website. 

Day 2
Continue working on the webpage from HW1
1. Add a second page and connect the two to make a website to tell us more about you (hobby, favorite show, interesting fact, etc )
2. Create a nav bar and link the two pages (this needs to be on both pages)
3. Make sure the headings on both page look similar, so that it seems you’re on the same website
4. Find a way to add a table to one of the pages
5. Add or embed a multiplemedia
6. Change the default color or font of headings and paragraphs
 
  HTML Elements: Tables
● Create a new table row to enter table heading or table data
○ <tr>add a new row to the table </tr>
○ <th>add a heading to that row </th>
○ <td>add data to the row <td>
  
 Using HTML tags: Video - attributes
 ○ ○ ○
Control – adds video controls, like play, pause and volume.
Autoplay – starts the video automatically
Width and Height – controls the size of the video on your browser. It is recommended to always include width and height attributes. The page will change ( or flicker) while the video loads if the height and width are not set.  

● <video> tag specifies a video or movie to be added to the page
● <source> definies multiple media resources for media elements, such as <video> and <audio>
  
 HTML Video Attributes Adding a YouTube video to HTML
● To embed a video from web such as youTube;
○ Click on share under a video
○ Click Embed
○ Copy the <iframe> tag
○ Include an <iframe> TAG in your web page
○ Use the width and height attributes to specify the dimension of the player
  
  HTML Elements: Navigation Bar
● When your website has more than a single web page, a navigation bar would help users get around
● Menu or navigation to a web page can be added in two way
○ Using lists - Vertical Nav Bar
○ Using Nav tag in HTML - Horizontal Nav Bar

  Create a Nav Bar using lists
● Create an unordered list and menu items
● Add Links to the list items
 
 Look up examples once again due to these not showing in Readme
LINK the Nav Bar
  <body>
    <h1>Hi, lets link stuff.<h1>
      <nav>
        <a href=""> Page 1 </a>
        <a href=""> Page 2 </a>
      </nav>
      
   Using HTML tags: Div
● <div> </div> is like a container of other HTML elements.
● Used to divide your html into different sections (will be more useful when styling the page)
● Wrap elements in div tag and it will look like a block container on the page with stuff in it.

● Add a navigation to your webpage

 Second Web Page
● Create a separate HTML page named stories.html
  
I called it Page 2 up above

● Create a second web page and link the two pages to create your first website

Added Exercises using CSS
Let’s style your website from last HW
1. Underline your name
2. Let’s change font size of all paragraph text
3. Change the font style of list of three of your favorite things
4. Change the background color of entire webpage
5. Change the color of all the anchor tags (linked text) to purple

About CSS

 CSS Declaration
● Consists of a selector, property and attribute selector Property : Value
H1 {
         Color: red;
    Background-color: black
    Font-style: italic;
} 

  CSS Declaration
● Selector:
○ Indicates the name of the TAG you want to change the appearance of.
Note: this affects all TAGS of that name. ■ Ex: h1
● Property:
○ Indicates the change you are making to this TAG.
■ Ex: h1 { color , font type , size... ● Value:
○ Indicates the value you want to give the property.
■ Ex: h1 { color: red, font type: comic sans, size: 16pt ...

      Adding CSS to HTML
● Add <style></style>tag within HTML doc

 CSS: Customize your fonts
● What can you do to style your font?
○ Change color
○ Change font style
○ Change font weight
○ Add font decoration
○ Change font size
○ Change letter spacing
○ And more...?
  
   CSS: Customize your fonts cont.
● Property for bold: font-weight ○ h2{ font-weight: bold }
● Property for Italic: font-style ○ h3{ font-style: italic}
● Property: text-decoration
○ {text-decoration: overline} inserts a line over the text
○ {text-decoration: line-through, strikethrough} places a line through the text
○ {text-decoration: underline} places a line below the text; such as a link.
○ {text-decoration: none}
● h1 {text-decoration: underline blue}
 
 CSS: Customize your fonts
● Property: text-transform
○ {text-transform: capitalize} turns the first letter of every word into uppercase
○ {text-transform: uppercase} turns every letter into uppercase
○ {text-transform: lowercase} turns the first letter of every word into lowercase
○ {text-transform: none}

 CSS: Customize your fonts
● Properties: letter-spacing, word-spacing, line-height, text-align
● letter-spacing and word-spacing properties manipulates the space value between words and letters.
● The line-height property sets the height of the lines in tag without adjusting the size of the font.
● The text-align property will align the text inside a tag to left, right, or center Example:
ex: p {
letter-spacing: 0.5em;
word-spacing: 2em; line-height: 1.5; text-align: center;
}
 
 CSS: Customize your fonts
● h1 {font-size: 12em or 12px, or 12pt or 12%}
● Lengths and Percentages:
○ Em – is the unit for the calculated size of a font. ■ EX: “2em” is two times the current font size.
○ px - is the unit for pixels. ■ 12px
○ pt - is the unit for points. ■ 12pt
○ % - is the unit for percentages. ■ 80%
○ Other units include pc (picas), cm (centimetres), mm (millimetres) and in (inches).
 
 CSS: Customize your text
● CSS has access to 16,777,216 unique colors.
● body {background-color: “red” or “rgb(255,0,0)” or “#ff0000”}
○ Red
❏ Is the same as rgb(255,0,0); Which is the same as; rgb(100%,0%,0%); Which is the same
as; #ff0000; Which is the same as #f00
○ There are 17 valid predefined color names. They are aqua, black, blue, fuchsia, gray, green, lime, maroon, navy, olive, orange, purple, red, silver, teal, white, and yellow.

 CSS Colors: Hexadecimal and Decimal colors
● hex color code in detail ○ #ff0000 :
■ # indicates that it’s a hexadecimal number for color
■ ff or first two digits represent color red’s intensity
■ second and third digits together represent color green’s intensity
■ last two digits represent the intensity of blue in our color
● decimal color code ○ rgb(255,0,0)
■ 255 represents the intensity of color red
■ second digit represents the intensity of color green
■ third digit represents the intensity of color blue
 
 CSS: Text Color and Background Properties
● Text color property: color
● Background color property: background-color
 ○ EX: ■ ■ ■
h1{ color: yellow; background-color: blue; }
body { font-size: 0.8em; color : navy; } h1 { color: ffc; background-color: #009; }
● Note: you can apply the same properties to different selectors (TAGS)

 
Day 3 
 Exercise
❏ Give all four divs different background-color
❏ Dive all four divs a border

  Div tag : HTML and CSS
❏ <div> </div> is like a container of other HTML elements.
❏ Wrap elements in div tag and it will look like a block container on the page with stuff in it.
 
 Span tag: HTML and CSS
❏ <span> tags are used to wrap content within your HTML elements
  
 HTML Input Tags
❏ HTML has a tag for form <form></form>
❏ Create a form in the body of your page
❏ <input> tag is used to create an input field
  <input type = “text” name = “FullName” placeholder = “full name”>
  
  TASK
❏ Create a form on your home page to ask user for any input

  CSS: Hover Selector
❏ The :hover selector is used to manipulate an elements attributes when you mouse over them.

 CSS: Hover Selector
❏ By default, #box1 will have a background color of blue.
When the mouse hovers over #box1, the background color will change to orange.


  HTML Tag: Link - Adding an external .css file
❏ Link tag is used to add CSS (JavaScript and more) file into a HTML page
 ⃞ ⃞ ⃞
rel → relation of the link ; it’s a stylesheet
type → type of the link; it’s a CSS text
href → path to the file that contains all the styling( folder/filename )
 ❏ When styling multiple pages of a website
⃞ good practice is to separate the style from HTML using a separate .css file ⃞ Using a separate file for style keeps the style consistent across pages  
  Add an external .css file
❏ Add an external .css file and link in the head tag of the html file
❏ Move all the styles from HTML to the css file
❏ On the same level as index.html file
⃞ Create a folder name css
⃞ Inside css folder, save css file as style.css
❏ Link the css file in html <head>
 
 
  Add an external .css file
❏ Watch for the path to the style.css
⃞ Here, index is the file where stylesheet is being linked.
  
    Folder Structure
● index.html : This is your landing page
● css/ : This is where you save your main.css file
● images/ : This is where you save all of your images
○ pic.jpeg
○ pic2.png
○ pic3.gif
● pages/ : This is where all other pages get saved:
○ about.html
○ gallery.html
 
 
1. Make sure you a folder structure for your website (see previous slide)
2. Create a single style.css file and move styling in this file for both of your web pages
3. Make sure both pages have
 a. b. c. d.
4. Add
5. Use
Same page background color
Same style for <h1> <h3>
Same font in both pages
Same layout/box model applied to both pages
a form on one of your pages. You can use this to ask visitors for suggestions or anything else you like id selector to style a paragraph on only one of the page
  
  Finish up your portfolio website.
1. Go over the assignment instructions and make sure you’ve all the required HTML tags
2. Use at least two of the position properties for your images and divs
3. Can you change the default display property of at least two elements
4. Submit your assignment. 
 
 
 
