# things-html-preview

## html preview


Example:

```html
    <things-html-preview
      srcdoc="<marquee>Things HTML Preview</marquee>"
      height="600"
      width="450">
    </things-html-preview>
```

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install


## Playing With Your Element

If you wish to work on your element in isolation, we recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polymer-cli

And you can run it via:

    polymer serve

Once running, you can preview your element at
`http://localhost:8080/components/things-html-preview/`, where `things-html-preview` is the name of the directory containing it.
