_template
=========

Template with frameworks, jade, less (included bootstrap less), and coffeescript

===========================
Syntax
===========================

bootstrap css vars, using syntax camel case, ex. @gridColumnWidth, @gridColumnWidthFluid, etc.
custom css vars, class, and ids, using css syntax, separated by hyphen, ex. .box-grid, @font-color-gray, class="box-grid", id="box-grid", etc


===========================
Development
===========================
The folder assets, include files for development, organized by following folders

pages - jade files
pages/includes - includes for jade files
styles - main files included in style.less (more details below, in Styles section)
style/pages - style for specific pages/sections
scripts - coffeescript files


=========
Pages
=========

Compiling into html pages, by default, include following files

head.jade - define meta title, metatags, and stylesheets
scripts.jade - included after body content, add html5shiv.js, jquery.js (1.7), and application.js (main)


=========
Styles
=========
Included on head.jade, compiling the following files

/*bootstrap*/
variables.less - declare bootstrap variables 
mixins.less - function utils for code
reset.less - bootstrap reset
responsive.less
grid.less


/*utils*/
elements.less - custom functions utils for code

/*custom*/
custom-reset.less - custom reset, and below override bootstrap properties necessary
assets.less - define buttons, links, image sprites, and others
fonts.less - define embeded fonts

general.less - define style general for app
/*files with stylesheet specific for each page, or section of app



=========
Scripts
=========
By default, have a method main, done for implementation, and initially not have included files.





===========================
Production
===========================
Following files, are delivered

*.html - static html's
resources - all resources, images, pdfs, fonts, stylesheets, scripts


