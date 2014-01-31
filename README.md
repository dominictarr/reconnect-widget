# reconnect-widget

A widget to display connection status, use with `reconnect-core`.

Green means connected, red means disconnected. If disconnected,
the number is countdown to the next connection attempt.

``` js
var widget = require('reconnect-widget')

//use reconnect-core with shoe
var reconnect = require('reconnect-core')(require('shoe'))

var r = reconnect(function (stream) {
  ...
})

//add the widget to the page.
document.body.appendChild(widget(r))

```


## License

MIT
