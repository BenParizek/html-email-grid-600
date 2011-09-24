
### Grid 600: Party like it's 1990

Inspired by the simple, rapid web development made possible
by CSS Frameworks such as the 960 Grid System and 
Blueprint CSS, this is a work in progress to try to 
simplify and modularize development of HTML emails.


### HTML Email Reset CSS

An attempt at a dumbed down reset.css to standardize the 
limited and archaic scope of HTML elements across email 
clients.


### HTML Email Grid

Several different grids can be supported as long as they 
fit the general grid requirements: 12 Columns for content,
12 columns for gutters (with one of those gutter columns
being split in two, half appearing as the first gutter on
the left and half appearing as the final column on the 
right).  A few of the most common grids:

GRID 3020
Columns: 30px
Gutters: 20px (Left & Right Gutters: 10px)

GRID 2030
Columns: 20px
Gutters: 30px (Left & Right Gutters: 15px)

GRID 1040
Columns: 10px
Gutters: 40px (Left & Right Gutters: 20px)


### HTML Email Utility Classes

These are a little more presumptuous than the reset styles
and try to establish a baseline for styling certain types
of common elements such as header tags, paragraph tags, 
bulleted lists, and images.  Depending on the email, these
styles may need to be adjusted, but hopefully the conventions
established here can be useful in any email markup.


### HTML Email Mobile Styles

These styles hope to simplify developing emails that are both
web-friendly and mobile-friendly.  They should only be used on 
one column layouts in their default form.  If multiple column
grid elements are used, these styles will need to be customized
or removed.


### HTML Email Modules

Modules are meant to extend the grid, standardizing how several 
different common design patterns can be coded with minimal 
customization.  Modules should be able to be dropped into any 
grid column with only the need to adjust their width, and perhaps 
add some css to the header (or shall it just be inline? we are 
trying to be modular!). 

Some current modules are the bulleted list and bulleted list with images.
Have you solved a common email design pattern with code? Share it!


### Dummy (and less dummy) Images

While waiting on assets, drop a few dummy images into your 
templates, including the amazing lightish-red!

I've also started pulling together a social media icon library
and a horizontal divider image library. Currently, the icons 
for several popular social media sites, and probably several 
less popular ones are in sizes 24x24 and 32x32.  Currently,
the divider library is lame.


### HTML Email Design Template (Get the designers involved too!)

A PSD Template which hopes to integrate a reminder of the 
limits and trade-offs of emails into the design process and provide
designers with the various grid options we can easily code for.

