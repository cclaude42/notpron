# Turn me ON!

Level three plays a strange sound, and occasionally shows the words `Stop being so negative!` in a flash.

Exploring the page source highlights this HTML comment :

```
<!-- read the whole url -->
```

The URL in question is :

```
http://www.deathball.net/notpron/false/movetotheothersite.php
```

This, combined with the "stop being so negative" comment, leads us to change the `false` to a `true` :

```
http://www.deathball.net/notpron/true/movetotheothersite.php
```

This takes us to level 4.