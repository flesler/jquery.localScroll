# jQuery.localScroll

Animated anchor navigation made easy with jQuery

### Demo

You can check the [demo](http://demos.flesler.com/jquery/localScroll/) to see the plugin in action.

### Installation and usage

Via [bower](https://github.com/flesler/jquery.localScroll/blob/master/bower.json):
```bash
bower install jquery.localScroll
```
Via [npm](https://www.npmjs.com/package/jquery.localscroll):
```bash
npm install jquery.localscroll
```

### Using a public CDN

CDN provided by [jsdelivr](http://www.jsdelivr.com/#!jquery.localscroll)
```html
<script src="//cdn.jsdelivr.net/jquery.localscroll/1.4.0/jquery.localScroll.min.js"></script>
```
CDN provided by [cdnjs](https://cdnjs.com/libraries/jquery-localScroll) (outdated)
```html
<script src="//cdnjs.cloudflare.com/ajax/libs/jquery-localScroll/1.3.5/jquery.localScroll.min.js"></script>
```

### Downloading Manually

You can get the latest stable version from the [releases page](https://github.com/flesler/jquery.localScroll/releases).

### jQuery.scrollTo

This plugin requires [jQuery.scrollTo](http://github.com/flesler/jquery.scrollTo).
In order to use jQuery.scrollTo 2.0 you need to update jQuery.localScroll to 1.4.0 and above.

### Notes

* The hash of settings is passed in to jQuery.scrollTo, so, in addition to jQuery.localScroll's settings, you can use any of jQuery.scrollTo's. Check that plugin's documentation for further information.

* If you want to convert the links from ALL over the page, with the same settings, just call $.localScroll(...) instead of $(...).localScroll(...)

* Most of this plugin's defaults, belong to jQuery.scrollTo, check it's demo for an example of each option.
