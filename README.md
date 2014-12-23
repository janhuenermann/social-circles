social-circles - Social media buttons
==============

Well designed social media buttons that are simple to use, just work and look good.

How to use
==============
Just copy the the /fonts and /css directories in your root directory of your web application. Then link the css file /css/social-buttons.min.css in your main html file with the following syntax
```
<link rel="stylesheet" href="../css/social-circles.min.css">
```

Then if you want an social button add the class 'social-button' to your a-tag and choose from one social network of the table at the bottom of the page and add their class for the icon. Next add an button type (that you can choose also at the bottom of the page) to the class and you're done. Congratulations, you've added your first social media button!
For everybody who could not follow this text here are a few examples:
```
<a class="icon-twitter social-button color" href="http://twitter.com/username"></a>
```
```
<a class="icon-instagram social-button grey" href="http://instagram.com/username"></a>
```
```
<a class="icon-rss social-button color" href="http://yoursite.com/rss"></a>
```

# Icons

Social network | Class
------------- | -------------
Facebook | icon-facebook
Twitter | icon-twitter
Instagram | icon-instagram
Behance | icon-behance
Vimeo | icon-vimeo
Youtube | icon-youtube
Google+ | icon-googleplus
RSS | icon-rss
Pinterest | icon-pinterest
Tumblr | icon-tumblr
LinkedIn | icon-linkedin
Skype | icon-skype

# Button types
**'color'** buttons are transparent but turn into the color of their brand when you hover over them with your mouse.

**'grey'** buttons are just grey. When you hover over them they jump up.

# Additional options
**'no-animation'** turns off all animations.

**'static'** turns off all custom behaviour when the user tries to interact with the buttons, for example hovering.

Acknowledgements
==============
Original icons are created by Daniel Oppel and you find them on dribble  (https://dribbble.com/shots/1509889-Free-Social-Media-Icons). I merged them into a font file so it is much easier to access them in the web.