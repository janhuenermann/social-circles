Social circles
==============

![Preview](images/preview.png?raw=true)

Well designed social media buttons that are simple to use, just work and look good. Give them a try at http://janhuenermann.github.io/social-circles/

For feature requests please create an issue.

Features
==============

- Well designed brand icons and logos
- Vector graphics loaded as font for fast loading and easy scaling
- Just about 7kb size
- Animations and custom designs specified per class
- No more than one line per button
- 13 different networks with over 75 button variations 


How to use
==============
Just copy the the /fonts and /css directories in your root directory of your web application. Then link the css file /css/social-buttons.min.css in your main html file with the following syntax
```
<link rel="stylesheet" href="../css/social-circles.min.css">
```

Then if you want an social button add the class 'social-button' to your a-tag and choose from one social network of the table at the bottom of the page the class and it to your tag's class as well. Next add an button type (that you can also choose at the bottom of the page) to the class and you're done. Congratulations, you've added your first social media button!
For everybody who could not follow this text, here are a few examples:
```
<a class="icon-twitter social-button color" href="http://twitter.com/username"></a>
```
```
<a class="icon-instagram social-button grey" href="http://instagram.com/username"></a>
```
```
<a class="icon-rss social-button borderless static" href="http://yoursite.com/rss"></a>
```

# Icons

Social network | Class | Brand color
------------- | ------------- | -------------
Facebook | icon-facebook | #3b5998
Twitter | icon-twitter | #4dc8f1
Instagram | icon-instagram | #3e739d
Behance | icon-behance | #0683f1
Vimeo | icon-vimeo | #86c9ef
Youtube | icon-youtube | #ce332d
Google+ | icon-googleplus | #d13f2d
RSS | icon-rss | #f88b02
Pinterest | icon-pinterest | #cb2028
Tumblr | icon-tumblr | #274152
LinkedIn | icon-linkedin | #0275b5
Skype | icon-skype | #03aceb
Github | icon-github | #4183C4 

# Button types
**'color'** buttons are transparent but turn into the color of their brand when you hover over them with your mouse.

**'grey'** buttons are just grey. When you hover over them they jump up.

**'borderless'** buttons are just plain icons that will get their brand color on hover.

# Additional options
**'no-animation'** turns off all animations.

**'static'** turns off all custom behaviour when the user tries to interact with the buttons, for example hovering.

If you wish to alter size, change the font-size of the buttons you want to change size of.

Acknowledgements
==============
Original icons are created by Daniel Oppel and you find them on dribble  (https://dribbble.com/shots/1509889-Free-Social-Media-Icons). I merged them into a font file so it is much easier to access them in the web.
