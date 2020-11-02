# Cpnt262-a2 - Dynamic animals gallery

by  Lynn Chen     Nov, 2, 2020



## Comments

At first , I thought it will be easy if I can complete this assignment following Tony's reminder in the starter code step by step. However ,I met some problems in the end when I created the image card for each image and appended the `<figure>` card to the `outputHTML` variable. I spent much time doing the code of the paths of images.  I'm not too familiar with JS syntax till now so the images shown on live pages were broken. I considered using "src= ${animal.imagePath}" in the beginning, then I changed it to "img src="images/${animal.fileName}" " from Tony's sample code in class. Both of them can make the images show well.

 I linked images to Lorem Picsum using "<a href="${item.title.toLowerCase()}.html">Lorem Picsum Link</a>", but there was an issue that it showed "Cannot GET /puppy.html" on the live server when I clicked the links. I debugged it many times before it showed up. Therefore, I decided to try an easier way as "<a href="${animal.url}">Lorem Picsum Link</a>". Good, it worked well, but I do not know whether this way is right. ：D

After starting JS, I found our course is much harder than before. Even though the coding works well sometimes, I do not totally understand the meaning of some coding when I just copy them by following Tony's sample code or the information online. What I need is more time and more try.



## Attributions

Thanks for the help from Emil who helped me about fixing the image path.



some code come from Tony's sample code in class  [SAIT WBDV](https://sait-wbdv.github.io/) 

like: https://github.com/sait-wbdv/in-class/blob/main/week07t/foreach/index.html

https://github.com/sait-wbdv/sample-code/blob/master/backend/express/1-animals-static/public/js/app.js

https://sait-wbdv.github.io/sample-code/frontend/galleries/grid-auto-fill/

Some Code in this project come from Tony Grimes's Codepen: https://codepen.io/browsertherapy 

like: [Simple Grid Checker Pattern](https://codepen.io/browsertherapy/pen/ExKJobK)



## Links

- GH repo:
- GH Pages demo:

Thank you for teaching!