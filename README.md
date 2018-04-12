# Step to install your font to dompdf in laravrel 

1. download load_font.php and place in ur project root
2. download your chinese supported font at eg: [Fonts-Unicode-Chinese](https://cooltext.com/Fonts-Unicode-Chinese) and place at your project root
3. run in commandline  `php load_font.php xxxfont xxxfont.ttf` .
+ eg: you have download simsun.ttf you will do `php load_font.php simsun simsun.ttf` then you font will be installed to storage/fonts directory
4 .use the font in ur template font-family: simsun.
5. enjoy!
