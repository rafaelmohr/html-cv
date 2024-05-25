# Small CV "Framework" for a HTML CV printable from the Browser

Different languages can be added as JSON Files, following the structure from ```language.json```.

Open ```cv.html``` in your browser, and specify language with the ```lang``` GET-Parameter, e.g. 
```
127.0.0.1:8080/cv.html?lang=de
``` 
will load file ```de.json```

The HTML is rendered using the [Handlebars Template Engine](https://handlebarsjs.com/).
JS gets loaded from CDN, works without NPM.

Changes to structure can be made in ```template.handlebars```.

Also, add ```photo.jpeg``` to root directory.
