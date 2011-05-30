Node Utf-8 Encoding/Decoding Functions
==============================================================================
This is a port of the work done by Chris Veness over the past ten years in relation
to encoding and decoding Utf-8 data in a JavaScript environment. I didn't write the core
of this, merely modified it to work with Node's package structure and be published on npm, where
people can by and large get used to it and stop being confused about this issue. ;P


Installation
------------------------------------------------------------------------------
    npm install utf8


Usage
-------------------------------------------------------------------------------
``` javascript
var utf8 = require('utf8');
    
var c = utf8.encode("私は")
utf8.decode(c);
```


Questions, Comments?
--------------------------------------------------------------------------------
**[@ryanmcgrath](http://twitter.com/ryanmcgrath/)**
