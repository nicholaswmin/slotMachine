This was written 15 (maybe 13-ish?) years ago when I started dabbling in JavaScript, I think.

This is by far the most badly written and ridiculous piece of shit I've ever written.
It's also the most starred.

Unfortunately it seems I've fixed the code style out of shame about a decade ago.

The original implementation was doing some funny weird shit with globals, 
trying to emulate an array-like list or something because I didn't 
know how to work with Arrays.

Enjoy - this is my magnum opus. 

Demo: nicholaswmin.github.io/slotMachine


### SlotMachine.js

--------------

  - Uses Paper.js - An HTML5 canvas wrapper for easier shape manipulation
  - Plug+Play  - define your own fruit images in index.html 
  - Uses `Math.Random()` to generate a seed.


##### Tech used

* [Paper.js]
* [jQuery]


##### Changing the fruit images

 - Some images are already defined in index.html.  
 - You can change their src's to the one's you want
 - Pay attention to the image id's/classes, widths & heights. Make sure you match them


##### Where are the results logged?

 - In the console


##### License
----
**MIT**

Author: Nicholas Kyriakides(@nicholaswmin)




[Demo]:http://nicholaswmin.github.io/slotMachine
[Paper.js]:http://paperjs.org
[jQuery]:http://jquery.com
