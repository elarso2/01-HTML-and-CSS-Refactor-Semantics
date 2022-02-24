The goal of this assignment is to take a pre-written code, with poor semantics, and make edits to both the HTML and css files to create a more semantic code, which would be more user and screenreader friendly. 
The final piece of code is meant to be meaningful, while not adjusting the overall appearance and function of the original website.

The most common tag in the original code was div, which means nothing to a screenreader. I began by first changing the div tags at the top and bottom to header and footer tags. 
I then changed another div to a nav which corresponds with the navigation bar at the top of the webpage.
Several other div's were changed to h2, h3, section, and aside as necessary. Also adjusted the div surrounding the section tags to be a main. None of these changes affected the appearance of the webpage, but are helpful for impaired users of the site who may be using a screenreader to navigate it.
Changes were made in css as several div tags were removed, replacing class calls with the appropriate tag names, i.e. header, nav, footer. 

Class names were removed or consolidated for many of the sections in index.html. The classes associated with the SEO, Online Reputation Management, and Social Media Marketing sections were each renamed to "mainSection". The original style.css had a block of code for each of the three sections, despite the fact that the same commands were being written for each of these elements. By giving them all the same class name, I was able to eliminate two of the three repetitive css blocks, thus shortening my css code and making it easier to adjust each element at the same time.
This same adjustment was made to the sections of the aside, both in the index.html and style.css files, by renaming each section "benefit", so the css could be consolidated.

None of the images had alt attributes in the original code, so I added those, both empty and with comments, to the HTML in order to make the images more accessible for sight-impaired users. 

My final site product looks like

![Final semantic Horiseon webpage with navigation bar, main section, aside, as well as header and footer.](./assets/images/HoriseonScreenShot.png)

My live website can be found by clicking [here](https://elarso2.github.io/01-HTML-and-CSS-Refactor-Semantics/#social-media-marketing).


