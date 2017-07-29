# timed-colored-log
A small revamp of console.log and console.error, adding time banners before messages and coloring errors in red.

## Usage

If there is no error:
```javascript
var log = require('timed-colored-log');

log('No error');
```

If there is an error:
```javascript
var log = require('timed-colored-log');

log('An error', true);
```
