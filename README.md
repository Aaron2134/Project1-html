Sources of information on overview page paragraphs
https://www.cbr.com/elden-ring-best-game-ever/#elden-ring-has-an-amazing-open-world
https://www.cnet.com/tech/gaming/why-the-hell-is-elden-ring-so-popular/
https://ftw.usatoday.com/lists/what-is-elden-ring
https://eldenring.wiki.fextralife.com/Elden+Ring+Wiki

Credit to Video Creator - on overview page
https://www.youtube.com/@BrandSanderson

What i used to add the videos 
https://support.google.com/youtube/answer/171780?hl=en#:~:text=How%20to%20Embed%20a%20YouTube%20Video%20on%20a,into%20your%20blog%20or%20website%20HTML.%20See%20More.

Sources of informations on map page paragraphs
https://eldenring.wiki.fextralife.com/Maps
https://www.ign.com/wikis/elden-ring/How_to_Reveal_the_Elden_Ring_Map
https://www.youtube.com/watch?v=Kh0TcNNXYYk

Credit for the interactive map div 
https://mapgenie.io/elden-ring/maps/the-lands-between

I Used guides on https://www.w3schools.com/html/html_iframe.asp#:~:text=The%20HTML%20%3Ciframe%3E%20tag%20specifies%20an%20inline%20frame,border%3Anone%3B%20to%20remove%20the%20border%20around%20the%20iframe for the interactive map

All the information on the 3 hardest bosses was taken from here
https://www.denofgeek.com/games/hardest-elden-ring-boss-fights-tough-difficult/

some inspiration for the website design
https://eldenring.wiki.fextralife.com/Elden+Ring+Wiki

Some code templates used in this project were taken from the love running example website and https://www.w3schools.com/Css/default.asp

I used guides on https://css-tricks.com/snippets/css/a-guide-to-flexbox/ for my navigation styling

Testing
The overview page passed the tests on the w3c HTML Checker except for the iframe element i was unsure on how to resolve the issues.
The Map page passed the tests on w3c HTML Cheacker with no issues found.
The Bosses page pasted the tests on w3c HTML checker except for having multiple uses of the id highlight but the code works as intended with it used multiple times so i decided to keep it.
The style.css passed the w3c CSS Checker with no issues found.

Bugs
I had issues with using python3 -m http.server it would always bring me to directory instead of my main page.
I then found out your main page needs to be index.html and i made the change to the file name and the nav links and it solved my issues

I have a issue with the images on the 3 bosses section i can't seem to get them to go under the text when on a smaller screen size