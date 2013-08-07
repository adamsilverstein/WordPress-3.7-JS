# Comments

* L70 can be reduced from `$(document).ready(function(){columns.init();});` to `$(document).ready(columns.init);`
* Needs JSDocs
* Variable declarations on line 1 are confusing but needed for backwards compatibility. There should be notes for this at the very least OR we should change the approach here to something that brings a little more clarity.
* Things like L49, L54, L73 are unsafe and need to be changed for safety in the event that something fails.
* jQuery objects need to be prefixed with `$` so we know they are jQuery objects when reading the code. i.e. - `panel` on L118
* needs a lot of cleanup from L162 to L420
* `.bind()` is deprecated (but still works) and the preferred method is `on` - see L423
* L378-L381 can be removed and changed to `e.preventDefault();`