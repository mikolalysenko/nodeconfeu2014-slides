parsed-url
==========
This incredibly trivial module is just a shortcut for:

```javascript
require("url").parse(window.location.href, true)
```

By requiring it you automatically get a completely parsed version of the URL that you can use in your document.

## Install

    npm install parsed-url

## API

```javascript
var url = require("parsed-url")
```

The object url is a representation of the window's location as a parsed url object.  The properties of this object are consistent with node.js' core [URL module](http://nodejs.org/api/url.html#url_url).

## License
MIT License