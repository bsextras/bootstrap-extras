Bootstrap extras
================================================================================
Extra JavaScript and CSS components for Bootstrap.

Third party tools
--------------------------------------------------------------------------------

### Grunt
### Jekyl

Helper
--------------------------------------------------------------------------------
Bs-extras will ship with a helper tool, mirroring some functionality of the [underscore][1] library. Proprietary methods aside, the helper tool will default to undercore methods if already present in the code. The reason for the separation is to keep the plugin light-wieght and to limit the number of dependencies.

Additionaly, the helper tool will include a number of DOM methods. Although bs-extras is a [jQuery][2] plugin, most DOM manipulations will be handled by native JavaScript for speed.

### DOM methods

`_.addClass(elem, className)`

`_.addClasses(elem, classNames)`

`_.addClassOnce(elem, className)`

`_.addClassesOnce(elem, classNames)`

`_.createElement(nodeName, [attrs])`

`_.dataAttrs(elem)`

`_.insertAfter(elem, target)`

`_.insertBefore(elem, target)`

### Object methods

`_.flattenJson(object)`

`_.flattenJsonArray(arr)`

### Intersecting methods:

`_.filter`, `_.flatten`, `_.clone`, `_.extend`, `_.extendOwn`, `_.isEmpty`, `_.isElement`, `_.isArray`, `_.isObject`, `_.isFunction`, `_.isString`, `_.isNumber`, `_.isBoolean`, `_.isDate`, `_.isNull`, `_.isUndefined`, `_.result`

CSS
--------------------------------------------------------------------------------

Components
--------------------------------------------------------------------------------

### Table

### Modal

### Datepicker

[1]: http://underscorejs.org/ "Underscore"
[2]: https://jquery.com/      "jQuery"
[3]: http://backbonejs.org/   "Backbone"
