# hugo-minis
Some easy-to-use Hugo shortcodes. 

  1. Pop these shortcodes inside the 'layouts/shortcodes' directory of your Hugo site.
  2. Call them using {{< shortcodeNameHere >}} inside your Markdown pages. 

Done.


## Slides
Copy the slider.html file into your shortcode folder. 
Add your numbered (e.g. Slide1.png, Slide2.png...) slide .pngs to a folder named 'slides' in the same directory as your page. Use the shortcode, like below:
```
{{<slider>}}
```
  
The shortcode looks for a folder named 'slides' by deafult. If your folder has another name, pass the folder name as a parameter like below:
``` 
{{< slider "myPhotoFolder">}}
```
## Thumbnails
Calling the thumbnail shortcode will print cards linking to each subpage, including a thumbnail and the page title.
