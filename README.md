﻿# miniFlappyBraille

A clone of http://flappybraille.ndre.gr/

golfed by @xem, @ilesinge, @aemkei, @subzey, @p01, ...

- Look at the URL.
- Play with arrows up and down.

**demo 1** (unminified, ES5): http://codegolf.github.io/miniFlappyBraille

**demo 2** (golfed, dirtier, ES6): http://codegolf.github.io/miniFlappyBraille/index.min.html

source code (213b / 197 chars)

````
b=[c=""];for(d=e=f=g=i=0;99>i;)c+="  "+"⡆⡅⡃⠇"[b[i++]=4*Math.random()|0];onkeyup=a=>d+=a.which-39;setInterval('3<e&&!(e%27)?i&&b[g++]==d?f++:i=0:h="⠈⠐⠠⢀"[d];location.hash=i?[h]+c.slice(e++/9):f',27)
````

**demo 3** (golfed, obfuscated in braille): http://codegolf.github.io/miniFlappyBraille/index.min.braille.html

source code (758b / 282 chars)

````
eval(unescape(escape("⡢⠽⡛⡣⠽⠢⠢⡝⠻⡦⡯⡲⠨⡤⠽⡥⠽⡦⠽⡧⠽⡩⠽⠰⠻⠹⠹⠾⡩⠻⠩⡣⠫⠽⠢⠠⠠⠢⠫⠢⡜⡵⠲⠸⠴⠶⡜⡵⠲⠸⠴⠵⡜⡵⠲⠸⠴⠳⡜⡵⠲⠸⠰⠷⠢⡛⡢⡛⡩⠫⠫⡝⠽⠴⠪⡍⡡⡴⡨⠮⡲⡡⡮⡤⡯⡭⠨⠩⡼⠰⡝⠻⡯⡮⡫⡥⡹⡵⡰⠽⡡⠽⠾⡤⠫⠽⡡⠮⡷⡨⡩⡣⡨⠭⠳⠹⠻⡳⡥⡴⡉⡮⡴⡥⡲⡶⡡⡬⠨⠧⠳⠼⡥⠦⠦⠡⠨⡥⠥⠲⠷⠩⠿⡩⠦⠦⡢⡛⡧⠫⠫⡝⠽⠽⡤⠿⡦⠫⠫⠺⡩⠽⠰⠺⡨⠽⠢⡜⡵⠲⠸⠰⠸⡜⡵⠲⠸⠱⠰⡜⡵⠲⠸⠲⠰⡜⡵⠲⠸⠸⠰⠢⡛⡤⡝⠻⡬⡯⡣⡡⡴⡩⡯⡮⠮⡨⡡⡳⡨⠽⡩⠿⡛⡨⡝⠫⡣⠮⡳⡬⡩⡣⡥⠨⡥⠫⠫⠯⠹⠩⠺⡦⠧⠬⠲⠷⠩").replace(/u../g,'')))
````

You can also play by executing the snippets above in your JS console!