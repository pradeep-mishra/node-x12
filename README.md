:exclamation: **NOTE: This project is no longer being maintained!** :exclamation:

# X12
A simple ASC X12 parser for NodeJS. Created originally for the [TC Toolbox](https://github.com/TrueCommerce/vscode-tctoolbox) project.

## Usage
```javascript

var x12Js = require("x12-js")

// parse (deserialize) X12 EDI
let parser = new x12Js.X12Parser(true);
let interchange = parser.parseX12('...raw X12 data...');
