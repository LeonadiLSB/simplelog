Simple logger plugin.

Just logs to the console, no file output (yet).
Supports colors and different log levels.

## Usage

```javascript
global.logger = require("simplelog");
...
global.logger.info("Message"); // debug|info|warn|error
```
