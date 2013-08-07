# Comments

* Great approach.
* Needs JSDocs
* $( 'body' ) could be cached with $( document.body )
* few variable names could be cleaned up for clarity
* Even though "private" functions are prefixed with `_` they are not truly private as this is an object literal and we can still access those public properties/methods. To make them truly private, we could implement a revealing module pattern. Though, this point is minor and eye-candy really.
* might help to move some of the anonymous callbacks in `.click()`'s and `.change()`'s to separate function and concentrate on a little more organization here.