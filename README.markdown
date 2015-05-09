# Cylon.js For DeviceHive

Cylon.js (http://cylonjs.com) is a JavaScript framework for robotics,
physical computing, and the Internet of Things (IoT).

This repository contains the Cylon adaptor for the [DeviceHive](http://devicehive.com/) M2M system.

For more information about Cylon, check out the repo at
https://github.com/hybridgroup/cylon

## Getting Started

Install the module with: `npm install cylon-devicehive`

## Examples

## Connecting

```javascript
var Cylon = require('cylon');

Cylon.robot({
  connection: { name: 'devicehive', adaptor: 'devicehive' },
  device: {name: 'devicehive', driver: 'devicehive'},

  work: function(my) {
    // provide an example of your module here
  }
}).start();
```

Explain how to connect from the computer to the device here...

## Contributing

In lieu of a formal styleguide, take care to maintain the existing coding style.
Add unit tests for any new or changed functionality. Lint and test your code
using `make test` and `make lint`.

## Release History

None yet...

## License

Copyright (c) 2015 The Hybrid Group. See `LICENSE` for more details
