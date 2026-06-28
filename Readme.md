# The Ultimate Interactive Birthday Surprise Template 🎂🎉

## Overview
Welcome to the most over-engineered, highly interactive digital birthday card you will ever find. 

Originally hand-crafted for a specific friend, this project has now been professionally scrubbed of all my personal inside jokes, sentimental letters, and highly questionable photos. What remains is a perfectly structured, ready-to-use template for *you* to customize. 

Feel free to fork this, add your own embarrassing media, take all the credit, and look like an absolute coding genius to your friends. 

## Features
* **The "Anti-Cheating" Security Protocol:** A highly sophisticated (read: very simple JavaScript) URL check (`?auth=true`) that forces the user to navigate the pages in the correct sequence. No skipping straight to the gifts!
* **Interactive Cake Cutting:** A CSS-powered cake that doesn't just disappear when clicked. Users must physically drag a digital knife to cut a perfect slice, which smoothly slides out to reveal the inner cake sponge. 
* **Mandatory Dopamine Release:** Triggered by a heavy barrage of automated CSS balloons and canvas-based sky-shot fireworks. 
* **The Triple Threat Surprise Envelopes:** Three aesthetic, side-by-side interactive envelopes containing:
  1. A custom video player.
  2. A fully functional photo gallery (with a click-to-zoom Lightbox feature so they can't hide from their bad angles).
  3. A vintage, scrollable aesthetic letter for your emotional (or roasting) needs.

## Folder Structure
* `index.html` - The starting point. (Users must start here, or the security script will kick them out).
* `questions.html` - A fun little questionnaire leading up to the main event.
* `surprise.html` - The interactive cake-cutting page.
* `letters.html` - The final page holding the video, gallery, and vintage letter.

## How to Customize (Make It Yours)
To transform this generic template into a personalized masterpiece, simply replace the placeholder files and text:

1. **The Video:** 
   * Drop your `.mp4` file into the main folder.
   * Open `letters.html`, find the `<source src="video.mp4" type="video/mp4">` tag, and change `video.mp4` to your file's exact name.
2. **The Photo Gallery:** 
   * Add your photos (both the good ones and the highly embarrassing ones) to the main folder.
   * Open `letters.html`, find the `<!-- PHOTO GALLERY -->` section, and update the `<img src="...">` tags with your image names (e.g., `img1.jpeg`, `img2.png`). You can copy and paste the `<img>` lines to add as many photos as you want.
3. **The Letter:**
   * Open `letters.html`, locate the `<div class="letter-body">` section, and type out your own birthday wishes. (HTML `<br><br>` tags can be used to create paragraph breaks).

## Deployment
To ensure your friend can actually view this on their phone without a computer science degree:
1. Do **not** send them a ZIP file. 
2. Drag and drop your completed project folder into **Netlify Drop** (or host it via GitHub Pages) to generate a free, live, and shareable web link.
3. Send the link and wait for the "OMG HOW DID YOU DO THIS?!" messages.

## License
This project is open-source. Use it, modify it, and spread the birthday joy!