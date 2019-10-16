# hugo-minis
Some easy-to-use Hugo shortcodes. 

  1. Pop these shortcodes inside the 'layouts/shortcodes' directory of your Hugo site.
  2. Call them using {{< shortcodeNameHere >}} inside your Markdown pages. 

Done.


# Slides
Copy the slider.html file into your shortcode folder. 
Add your slide .pngs to a folder in the same directory as your page. The shortcode looks for a folder named 'slides' by deafult. If your folder has another name, pass the folder name as a parameter like below:
``` 
{{< slider "myPhotoFolder">}}
```
