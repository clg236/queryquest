<img src="https://drive.google.com/uc?export=view&id=15DuvZMIZiMdyrGHJOSU3hpVfpYrlkvgN" alt="description of the image for screen readers">

# Description
"Query Quest" is an interactive fiction game created with Twine. Dive into a world of mystery and exploration, where your choices shape the story. Navigate through enchanting landscapes, encounter mystical creatures, and solve puzzles to unravel the secrets of the "Query Quest".

# How to Play
To play "Query Quest", simply open the HTML file in your web browser and embark on your journey.

# Importing the .twee File into Twine
1. Download this repository (or just the .twee file really)
2. Go to twinery.org
3. Open Twine and click Library, then "Import From File" button.
4. Navigate to the location where the "Query Quest .twee" file is saved, select it, and click "Open".
   
The game’s passages will appear in the Twine interface, and you can edit or play the game from there.

# Adding Custom Images
You can host your own images using Google Drive and then integrate them into the game using the <img> tag in Twine. Follow the steps below to make your images accessible and get the correct URL structure for use in the game.

1. Make the Image Publicly Accessible
2. Open the image's Google Drive link.
3. Click on the "Share" button.
4. Change the link sharing settings to “Anyone with the link can view.”
5. Get the File ID: Copy the file ID from the sharable link. It is the string of text that comes after /d/.

Example: For the shared image link https://drive.google.com/file/d/15DuvZMIZiMdyrGHJOSU3hpVfpYrlkvgN/view?usp=sharing, the file ID is 15DuvZMIZiMdyrGHJOSU3hpVfpYrlkvgN. Use the following URL structure inside your <img> tag, replacing FILE_ID with your file id: https://drive.google.com/uc?export=view&id=FILE_ID

