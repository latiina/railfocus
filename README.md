# Rail Focus
This one-pager has been created for a client as a template for an online newsletter which will be updated monthly and the URL sent via an email to those opted in to receive the email.

## HTML Template 
Each section has a START and END comment tag to help the client navigate around the HTML template.
Each main section has been coded independantly to enable movement and repetition of certain elements. Should this break, please reach out for a quick fix. Or you are welcomed to fix it yourself within the custom styles sheets.

## Style Sheets Explained 
There are two CSS files.
Each file is a SCSS file which pulls multiple SCSS files together. This is to avoid multiple style sheets upon rendering the page. And to the clients requirements.

The client will use php to instruct the page which style sheet to pull upon reading the readers device.

1) desktop.css
This pulls all the the following styles together to one stylesheet: 
    a) bootstap-reboot : template v4.2.1
    b) bootstrap : template v4.2.1
    c) jssor-slider : specific theme customised to clients requirements https://www.jssor.com/

    d) desktop-bootstrap-grid : seperated the bootstrap-grid template (v4.2.1) styles by desktop/mobile to fit with client requirement of having two seperate files.

    e) desktop-custom : all custom class and ids outside of boostrap


2) mobile.css
This pulls all the the following styles together to one stylesheet: 
    a) bootstap-reboot : template v4.2.1
    b) bootstrap : template v4.2.1
    c) jssor-slider : specific theme customised to client requirements https://www.jssor.com/

    d) mobile-bootstrap-grid : seperated the bootstrap-grid template (v4.2.1) styles by desktop/mobile to fit with client requirement of having two seperate files.

    e) desktop-custom : all custom class and ids outside of boostrap


## How to amend the SCSS Files 
To edit the custom style sheets I recomment you download Compass to you local machine but do not create a project as the config.rb is already within the folder.

How to download compass: http://compass-style.org/install/

Once downloaded you can open _mobile-custom.scss OR  _desktop-custom.scss files and make amends. 

Run the compass compiler for the .css files to update.

## Slider image sizes
There are two Jssor sliders on this template. 

1) Jssor_1- with thumbnails
    Main image recommended size 1200x635px
    Thumbnail 190x130px

2) Jssor_2- no thumbnails - recommended size: 790x525px


## Framework and apps used

Acknowledgements and appreciation goes to the following sites to enable putting this one-pager together:

- Boostrap https://getbootstrap.com/
- Jssor https://www.jssor.com/
- Daniel 'Eisbehr' Kern http://jquery.eisbehr.de/lazy/
- Lokesh Dhakar https://lokeshdhakar.com/projects/lightbox2/


