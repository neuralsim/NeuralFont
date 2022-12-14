# NeuralFont, an 8-bit scalable (fixed width) Font

This is a font I created myself, from scratch, because I needed a font with an 8-bit look to it. The image you see here is scaled, the real thing looks much better, save it and open it in a real image editor.

![customFont](https://github.com/neuralsim/NeuralFont/blob/main/neuralFont.png)


Ascii index string for all current symbols (26 per row as you can see in the image)
ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-+*@$!#%=&()/\\[]|;:'"?<>_.,{}~`^

It is designed to have an 8-bit look but also scale very well. The characters themselves are 9x9 pixels (but most are 7x7 in actual size with a couple of intentional exceptions, e.g. braces and lower-case j), and the border between them is 1 pixel. 

# Kerning 
...is of course required to make the font look good. I will add a kerning file eventually once I figure out the right format to use. I suggest you just play with it and develop your own kerning pairs, it's not hard, and it's worth it, the font looks very nice when properly formatted.

# Scaling 
...the font is easy for powers of 2, simply double the pixels each power. The font is intentionally "blocky" and meant to be fixed-width but it looks OK aliased if you need to alias it.

# If I add 
...any new characters, I will add them to the end, so you can update this with assurance that I won't break you (as long as you can handle an extra value you don't use, seems like it would be hard to create a bug that broke if there was extra data in the bitmap, but as a programmer I know and have confidence it can be done).

I believe all the standard ascii english characters are represented. If you want to request a character, or even a set of characters be added, I'm happy to do so. Just as long as what you're asking me to do is create my own version of them, not copy them from somewhere, and they have some kind of reference to some kind of extended ascii standard. Looking myself now I see I could use an english pound symbol and a Euro symbol.

I am releasing it into the PUBLIC COMMONS. This means it is completely free for anyone to use, extend, modify, change and even sell. Good luck with that last part.

What you CANNOT do with my font is very simple. You cannot claim it is your own font and nobody else is allowed to use it. I not only created it myself, I have extensive proof that I created it myself, and also proof of when I created it.

This is not legal advice, of course. If you are planning to use this in a commercial product and you want to see my evidence of ownership, contact me.

In short, if anybody sues you and says you stole their font, they're lying. This is an original work of art. Every single pixel in this font was carefully curated. In all this probably took about 8 hours to make and then a couple of months to perfect.

Enjoy!
