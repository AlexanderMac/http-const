# http-const
## WARNING :warning:: This repo is not maintained anymore.

HTTP constants: methods, protocols, headers, content types, etc.

### Installation

```
npm i -S http-const
```

### Usage

``` js
var httpConst = require('http-const');

console.log(httpConst.methods.get); // will output GET
console.log(httpConst.protocols.http); // will output HTTP
console.log(httpConst.protocolVersions.v10); // will output HTTP/1.0
console.log(httpConst.headers.contentType); // will output Content-Type
console.log(httpConst.contentTypes.formData); // will output multipart/form-data
```

### Author
Alexander Mac

### License
This code available under the MIT License.
See License.md for details.  
