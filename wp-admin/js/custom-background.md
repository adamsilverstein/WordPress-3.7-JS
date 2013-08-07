# Comments

* move `.click()`'s away from anonymous functions and into declarations or expressions
* move `.done()` promise on L64 to it's on function. Would be nice to fire off a JS hook here.
* could benefit from caching; multiple clicks continually lookup elements whereas caching prevents the multiple lookups, thus increasing speed for the user.
* needs JSDocs
* `$(this).val()` could be changed to `this.value` - no real reason for jQuery in that event - see L16 and L20 as examples
* needs to be moved to a revealing module pattern to remain consistent with other JS files