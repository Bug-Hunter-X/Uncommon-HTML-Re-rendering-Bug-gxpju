# Uncommon HTML Re-rendering Bug

This repository demonstrates an uncommon bug in HTML where an element's visibility doesn't update correctly after toggling its `display` property from `none` to `block`.  The bug is subtle and might only manifest in specific browser versions or under particular conditions.

## Bug Description
The `myFunction()` in `bug.html` attempts to hide and then show a div element.  However, after the initial hide, the div sometimes fails to reappear.  This is unusual because it's not a typical syntax error or obvious logical flaw. The solution file shows how to handle this.