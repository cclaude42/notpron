# say it loudly and proudly

Level 8 plays a strange sound, and shows the text :

```
JAY should PACK his stuff
```

We inspect the HTML and find a few interesting things :

```
<audio src="../stuff/mus1.mp3" autoplay loop></audio>
<au dio src="../stuff/mus2.mp3">
<!-- water became wine -->
```

The audio playing is `../stuff/mus1.mp3`. But we see an unused audio file in invalid HTML formatting : `../stuff/mus1.mp3`.

We go to `https://www.deathball.net/notpron/stuff/mus2.mp3`, but the file seems corrupted.

We download it and try to determine its type (using a tool, or a site like `https://www.checkfiletype.com`)

We find that the file is a JPEG. We rename it to give it the `.jpeg` extension, and we see :

![mus2.mp3](mus2.mp3.jpeg)

We click the guitar, use `inverted` and `tenthlevel` as username and password, and we get to level 9.