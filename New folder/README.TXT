------------------------------------------------General Notes for all layouts--BEGIN---------------------------------------------

Each of these layouts rely on a single stylesheet.

Each layout shares similar ID's and classes for easy cross development.

  A list of ID's that will be used on all layouts:
  #wrapper = This sets the fixed width of the page and allows for the height to be unlimited.
  #bottomSpacer = This sets a blank space on the bottom of the page so it matches the space on the top of the page. It acts like a margin.

  A list of classes that will be used on all layouts:
  fitImage = This allows the image to fit responding to the size of it's parent container.


    To add a new paragraph of text all that is needed is to use <p> YOUR TEXT </p> .
To replace the images I have provided, simple delete the src of the img attribute and add your own.

------------------------------------------------Notes for index.html--END---------------------------------------------

------------------------------------------------Notes for index.html--BEGIN---------------------------------------------

To use this template I have provided these guidelines.

Understanding the ID's:
  #image = This controls the size of the image container.

  Understanding the Classes:
  .item = This is the main holder for each item. The item is the wrapper for the image, heading and button.
  .heading = This is for a single line heading use.
  .doubleLineHeading = This is for a double line heading use.
  .button = This sets the background color and other styles of the button.

Adding an item to the page :
All that needs to be done is copy the code in index.html starting with with <div class="item"> tag to the closing </div> <!-- END item --> tag.

If you want to add three items at a time, you may copy the <!-- BEGIN row --> to <!-- END row --> tags.



------------------------------------------------Notes for index.html--END---------------------------------------------

------------------------------------------------Notes for Layout1.html--BEGIN---------------------------------------------

To use this template I have provided these guidelines.

Understanding the ID's:
  #heroImage = This controls the size of the image container.
  #content = This handles styling for all the content text below the header.

Understanding the Classes:
  .headingHero = This controls the styling of the header.



------------------------------------------------Notes for Layout1.html--END---------------------------------------------

------------------------------------------------Notes for Layout2.html--BEGIN---------------------------------------------

To use this template I have provided these guidelines.

Understanding the ID's:
  #imageRectangle = This controls the size of the image container and positions it to the right side of the page with content wrapping around the left side.
  #contentSideHero = This sets the styles for the content.

  Understanding the Classes:
  .headingSideHero = This handles the styles for the header.



------------------------------------------------Notes for Layout2.html--END---------------------------------------------

------------------------------------------------Notes for Layout3.html--BEGIN---------------------------------------------

To use this template I have provided these guidelines.

Understanding the ID's:
#imageSquare = This controls the size of the image container and positions it to the right side of the page with content wrapping around the left side.

  Understanding the Classes: No unique classes needed.


------------------------------------------------Notes for Layout3.html--END---------------------------------------------

------------------------------------------------Notes for styles.css--BEGIN---------------------------------------------

I provided these details to understand how to use styles.css:
  + Styles that are needed for all layouts are put in the top section of the stylesheet labeled Global Styles.
  +Styles that are needed for Layout1.html are in it's corresponding section with the same in respect to Layout2.html and Layout3.html.

  Specific details related to index.html :
    + If the gradient background is undesired then go to the .button class and delete all background tags and create a new tag of
      - background-color: YOUR COLOR ;
    + There are two styles that are not needed and are only provided if desired. They are:
      - a .button = makes the mouse icon on the screen to the pointer hand when hovering a button.
      - a .button:hover = if there is any desire to create a hover effect to the button.
------------------------------------------------Notes for styles.css--END---------------------------------------------
