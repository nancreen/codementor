# codementor

The repo contains the html page as it is integrated in the wider Django environment. All static files are loaded using Django syntax. 
The important thing to note is that most of the content is loaded by JS, which listens to messages from a websocket, and loads elements according to data from said messages. The repo also contains screenshots of how the page looks when it is loaded (with numbered elements).

As mentioned in the post on Codementor, I need help with figuring out how: 
1) to load elements from JS so that they are neatly arranged within the Boostrap grid; and
2) figure out a way to unify their design, and perhaps more importantly, learn how to design elements 
    so that I can efficiently change the overall styling of the page, despite generating elements with different JS modules.

Here is a brief explanation of what each element on the page does now, and what I'd plan to do with it:
Element 1 - this is a progress bar, it loads from JS. Will be redesigned to follow the desired styling of the page.

Element 2 - this is a textbox showing the speed of a site, and is loaded from JS. My idea was to make it into a spedometer, but as                 I found this to be somewhat difficult, it will just be incorporated into the new styling of the page.

Element 3 - this is an ordianry chart loaded from JS. Each bar will be transfered to a pie chart, which are arranged in a single/several horizontal rows.

Element 4 - also a chart loaded from JS. Will just be changed to fit into the global design of the page.

Element 5 - table loaded from JS. Also will just be changed to fit into the global design of the page, but cells in the collumn to the right need to change color based on the input from JS. 

Element 6 - this is a tree graph made using http://fperucic.github.io/treant-js/. The design of this needs to fit into the design of the page. This is the part where I'm really stuck, as I find it erally difficult to make any alterations to the design.

Elements 7 and 8 - will just make them fit into the new styling.

While this lesson is about helping me learn how to more efficiently work with FE and not going into the minute details of my specific design plans, I thought it might be usefull to list a couple of sites I like in terms of color scheme, fonts, general feel of the minimalist design:
- https://www.coderesolution.com/
- https://www.digitalasset.com/
- https://radicalwebdesign.co.uk/
