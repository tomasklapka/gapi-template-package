GAPI Template Package
=====================

This repo is used as a template to simplify creation of a new GAPI module

Usage
-----

Clone template package into a directory (example for new package gapi-foo)

```
git clone https://github.com/tomasklapka/gapi-template-package gapi-foo
cd gapi-foo
```

Remove *.git* folder:
```
rm -rf .git
```

Edit *package.json*:
```
$EDITOR package.json
```

gulp
----

See [gulpfile.js](gulpfile.js) for Gulp tasks.

Frequently used commands:
-------------------------

 * `npm install` - to install modules and trigger its *prepublish* script
 * `gulp` - to compile source files into JS and documentation
 * `npm test` - to run tests with coverage information
 * `node --harmony examples/lib/example` - to run compiled example.js script with harmony proxies if used
