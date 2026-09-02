<p>
  <img src="images/Notify-logo.png" alt="Noteify logo" width="150">
</p>

# Noteify

a note sharing platform built for my web dev class final project. users can browse notes, upload their own, like the ones they find useful, and search through everything from a simple grid layout.

## what it does

- browse all uploaded notes as cards with thumbnails
- create and upload new notes with an image or thumbnail
- like and unlike notes, with your likes remembered across visits
- search notes by title in real time
- dark mode toggle that stays saved between sessions
- view individual notes on their own page

## how it's built

frontend is plain html, css, and javascript. no frameworks, just vanilla code so i could actually understand what every part was doing.

backend runs on php, talking to a mysql database to store notes, thumbnails, and like counts.

- `index.html` - landing page
- `home.php` - main feed, pulls notes from the database and renders them
- `create.php` - upload form for new notes
- `view.php` - single note view
- `like.php` - handles like/unlike requests
- `liked_notes.php` - shows notes you've liked
- `upload_image.php` / `upload_thumbnail.php` - handle file uploads
- `style.css` - all the styling

## why i made it

this was my final project for web dev class. i wanted something that actually felt like a real product, so i built out the full flow: uploading, browsing, searching, and liking, instead of stopping at a static page.

## running it locally

you'll need a php environment with mysql support (xampp or similar works fine). set up a database, update the connection details, then serve the folder and open `index.html`.
