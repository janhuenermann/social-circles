Social circles
==============

![Preview](images/preview.png?raw=true)

Well designed social media buttons that are simple to use, just work and look good. Give them a try at http://janhuenermann.github.io/social-circles/

For feature requests please create an issue.

Features
==============

- Well designed brand icons and logos each with their specific colors
- Vector graphics loaded as font for fast loading and easy scaling
- Just about 5kb size
- Animations and custom designs specified per class
- No more than one line per button
- 13 different networks with over 75 button variations 

ToDo: SASS support

How to use
==============
Just copy the /fonts and /css directories to your root directory of your web application. Then embed the css file /css/social-buttons.min.css in your main html file with the following code snippet
```html
<link rel="stylesheet" href="../css/social-circles.min.css">
```

To create a button add the class 'social-button' to your anchors (a) and add the class of the social network you want the button to be, look at the table below. Now choose a button type, add it as a class and you're done. Congratulations, you've added your first social media button!
For everybody who could not follow this text, here are a few examples:
```html
<a class="icon-twitter social-button color" href="http://twitter.com/username"></a>
```
```html
<a class="icon-instagram social-button grey" href="http://instagram.com/username"></a>
```
```html
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
Dribbble | icon-dribbble | #ea4c89

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
Original icons are created by Daniel Oppel and you find them on dribbble  (https://dribbble.com/shots/1509889-Free-Social-Media-Icons). I put them into a font file to make them accessible for web browsers.
