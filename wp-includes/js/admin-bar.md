# Comments

* needs JSDocs
* not sure why L5 is minified?
* needs to be moved to a revealing module pattern for consistency
* `.click()` functions need to be moved from anonymous functions to independent function declarations/expressions
* could benefit from caching selector lookups
* `.bind()` is deprecated (still supported) but preferred use is `.on()`
* jQuery objects need to be prefixed with `$` for clarity when reading code
* variables on L173 are extremely confusing; could really use better naming conventions for clarity when reading code
* L192, `ul.nodeName` is already upper case
* L150-L155 can be removed and `addEvent` can be changed to use jQuery
* not sure why things are comma-separated for declarations/expressions on L170 for example. This is not an object literal but rather a function declaration and things require semi-colons and `var` prefixes.
* Overall, really needs a lot of help