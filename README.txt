# Popup entity Fork without content entity visibility dependency

This module allows creating custom and translatable entities that are shown as popups.

Popups allow:
- have translations
- put fields, as in any other entity
- have a visibility control similar to the configuration of the blocks
- configure how many times they are to be seen, what size they are, in which theme breakpoints to use (useful to avoid showing on mobiles or having different popups for different screen sizes), delay, ... etc

Use cases:
- simple popup with a body field to display a text on the home
- image + text popup that is only shown on pages of a specific content type
- Popups with images in different formats for different breakpoints (mobile, tablet, desktop, ...)
- show a popup warning for all pages of a content type in a certain language
- ....

NOTE: This module has a performance problem in its concept. All active popups will be loaded to calculate whether or not to display. If you have a few popups this should not be a problem, but if you intend to have 30 popups on your website ... this will surely affect performance.
