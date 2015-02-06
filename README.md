# CSS Push-out Menu
A CSS only push-out menu column

This push-out menu uses a checkbox and [General Sibling selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/General_sibling_selectors) to determine if the menu is shown.

At the time of writing this is untested but should be supported all modern browsers (ie9 up) and work on touch devices too. <=ie8 needs js to support css `:checked` selector. Selectivizr does this.

NOTES TO SELF:
 - General sibling selector (~) support is excellent (ie7+)
 - but :checked is not. Add Selectivizr or similar to this demo
 - I dont much like this checkbox solution for closing sub-menus as it makes the menu ugly. Perhaps there's a better way?

NOTES TO USER:
 - Want the menu to be open on load? Just set `nav-trigger` input to `selected`.


http://jsfiddle.net/moob/efnrqf6w/
