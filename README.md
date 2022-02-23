The goal of this assignment is to take a pre-written code, with poor semantics, and make edits to both the HTML and css files to create a more semantic code, which would be more user and screenreader friendly. 
The final piece of code is meant to be meaningful, while not adjusting the overall appearance and function of the original website.

The most common tag in the original code was div, which means nothing to a screenreader. I began by first changing the div tags at the top and bottom to header and footer tags. 
I then changed another div to a nav which corresponds with the navigation bar at the top of the webpage.
Several other div's were changed to h2, h3, section, and aside as necessary. Also adjusted the div surrounding the section tags to be a main. None of these changes affected the appearance of the webpage, but are helpful for impaired users of the site who may be using a screenreader to navigate it.
Changes were made in css as several div tags were removed, replacing class calls with the appropriate tag names, i.e. header, nav, footer. 

None of the images had alt attributes in the original code, so I added those, both empty and with comments, to the HTML in order to make the images more accessible for sight-impaired users. 

I then consolidated the css for my aside by combining elements into the same class, so I could have one block of code for each, rather than three blocks, thus eliminating some of the original redundancy in the css code. 
