## Example usage

```javascript
/* Using TavDiv */

// disable tabdiv processing on page load
Vex.Flow.TabDiv.SEL = null;

$(document).ready(function() {

    // tabdiv - parse, create canvas, and draw
    var tabDiv = new Vex.Flow.TabDiv("#tab");

    // initialize tab player
    var player = new TabPlayer(tabDiv, 60);

});

```