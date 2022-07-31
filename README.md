# Phase_One
HTML &amp; CSS Capstone Project

Link to project: https://stellar-belekoy-a003c2.netlify.app/


There are two main files in the project. First if the HTML file that contains the elements and provides the structure needed for the webpage. The HTML file in this project has been names index.html.
The CSS file which is also named style.css can be found within the folder named css next to the HTML file.
The CSS is responsible for the styling of the elements and the structures within the index.html file. The CSS is linked to the HTML file by inserting the <link rel"stylesheet" href="style.css"> format into the head section of the HTML file.

The entire design of the project went through 3 phases. These phases are:
the Desktop design phase
the Mobile design phase and
the Tablet design phase.

Throughout all the three design phases, the entire website was envisioned as having 3 main parts or main divs.

The nav tag was used to group the logo image and the first 'pre-order' button.
The nav tag was assigned a display property of flex.

The first main div encompasses the first block text which includes the H1 and the paragrag beneath which is also in its own 
div tag, in addition to the first keyboard image which also has its own div.
This first main div tag was given a class name of "first-row".
The first text block within the "first-row" class also has a class name "first-block" which allows that entire dive to be styled separately.
The second div with the same "first-row" div has a id name "first-row-imag-div" which allows the div containing the image to be style.
The "first-row" class was then given a margin-bottom property to provide space between that section and the next section.

The second main div contains the two other images and the second text block which has the h2 header.
The name assigned to this section of the HTML page was given a class name of "second-row".
The main second-row class contains sub-divs which were also included to help specify two main groups to allow stylyin.
The first sub-div within the second-row class was given the name "second-rown-images" which contained the two images in the second row. namely: the 'phone-and-keyboard' image and the 'keyboard-and-glass' image.
The images were assigned the desired heights and widths within the css stylesheet.
The second sub-div within the second-row class is also given the name "second-block".
The second-row class is assigned a property display value of flex which allows the two divs to line up one behind the other on the same axis.
The second-row class also has a margin-bottom property which allows the creation of space between the stated section and the next below.

The third and final main div was also assigned a class name of "third-block" and this div also had 4 main sub-divs to allow the preferred styling.
This third-block class was given a display property with value flex.
The four sub-divs within this class were given class names as well. The class names are:
'sub-one'
'sub-two'
'sub-three'
'sub-four'
These sub-divs were also given a width so as to keep them within a specific size.
The four sub-divs also contained sub-divs which provided room for the icon images which can be seen within the third-block section on the HTML page.
The third-block class contains a margin-bottom property which creates some decent amount of space between the third-block section and whichever section comes beneath.

A footer element was also added to the HTML code to cater for the 'copyright' text within the HTML file. This text was centered by using the text-align property in CSS.

The background color of the HTML page was left at the default which is #FFFFFF.
The font-family 'Barlow' was imported into the HTML file from the Google Fonts webpage.

All H1 headers were given a font-size of 56 pixels.
All H1 headers were assigned a line-height of 56pixels also.

All H2 headers were given a font-size of 32 pixels.
All H2 headers were given a line-height of 36 pixels.

All H3 headers were given a font-size of 24 pixels.
All H3 headers were given a line-height of 28 pixels.

All headers were transformed to uppercase elements by using the text-transform property in CSS.

All texts within buttons were were aligned in the center and were also transformed using the text-transform property.

The top right button was given a default background color of #E8EFF2. But was given an active color of #162542.
The second button was given a default background color of #F16718. But was also given an active color of #FF9B62.
Both buttons were given an active text color of #FFFFFF.


<!-- Mobile design -->
For the mobile design phase, a media query was written with the minimum width of 320px and a maximum width of 480px which made sure all the 3 main levels - Large, Medium, Small - of phone screens were captured.
With the mobile design phase the 3 main sections/divs all went under some small changes.

With the first-row class, the display was changed to block which allowed the first-row-image-div to fall to the second line/ the line below. 
The second-row also had the same display property changed to allow the second-block div to fall to the next line, thereby allowin the images only to stay on the same line.
The third-block div too was given a display value of block and its contents were centered in the middle of the page by using the margin-left and margin-right properties.


<!-- tablet design -->
With the tablet design, a media query with a minimum width of 480 pixels was set in conjunction with a maximum width of 800 pixels to cater for tablet screens.
Here also, a few changes were made. The second-row display property was changed to a block thereby allowing the second-block div to drop off to the next line.
The second-block div was also changed to an in-line flex which allowed the paragraph beneath the H2 element shift to the right side of the H2 element. A margin right was set for the H2 element which allowed a little space to to come between the header element of the second-block and its paragraph.


After all the work was done, a repository with the name Phase_One was created at gitHub and the link to the repository was created. VS Code was opened and the clone repository button was clicked which allowed me insert the link copied earlier. The changes were added to the staging area and were then committed. The changes were then pushed to the GitHub repository. The site was hosted using netlify.


