HLT @ Augsburg Website
====================

Adapted from Agency theme based on [Agency bootstrap theme ](https://startbootstrap.com/template-overviews/agency/)

# Add / update info on team members

Team members are listed in `_data/members.yml`.
Add their photo to `img/team` in a format of 200x200px.
A good open source tool to quickly bring your picture to the right format is GIMP: In the menu "Image," work with "Scale Image" and "Canvas Size."
Deutsch:
* "Bild" - "Leinwandgröße": auf Quadrat einstellen und Bildausschnitt wählen. "Größe ändern"
* "Bild" - "Skalieren": auf 200x200px ändern. "Bild skalieren"
* "Datei" - Bildname.jpg überschreiben "Exportieren"

# Add a post

All posts are in `_posts`.
File names have to start with their date.
I recommend that you copy a post of the type that you intend to create (News, Research activity, or Study course) and edit it. You have to increase the `modal-id` - please count the number of posts and use this number as the id (counts start at 1).
It is important to use the correct `category` value as this decides where a post is displayed.

# Adding an event
 Modify the file `_includes/events.html`.


# Open Questions

* We need a separate page (ideally not on the landing page) for an overview of the program of the weekly group meetings.
* I suggest we post offers for Bachelor/Master theses, job ads, etc. simply under news.
