# My-Website
My personal developer website

This is my website, I made it respecting all accessibility features.

I used a trick thst I figured out by myself to prevent the page to rearrange after a dynamic size image is loaded: I set the photo height very high with HTMLM attribute, so it will reserve space on the page, after the page it's loaded a JavaScript function set the image hight auto, so the image will be resized according to the CSS width property maneteing the right proportion, the only downwside it's that until the page it's loaded the image it's distroted in height but it usually last less then a second and prevent the under portion of the page to be shown before scrolling, this is very important for this site because there is an event listener that activate animations when the user view parts of the screen.
