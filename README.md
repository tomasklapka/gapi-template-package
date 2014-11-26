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

Remove .git folder:
```
rm -rf .git
```

Edit `package.json`:
```
$EDITOR package.json
```


Where to put CoffeeScript source files?
---------------------------------------

 * source files go to ./src
 * test source files go to ./test/src
 * example source files go to ./examples/src


gulp
----

See [gulpfile.js](gulpfile.js) for Gulp tasks