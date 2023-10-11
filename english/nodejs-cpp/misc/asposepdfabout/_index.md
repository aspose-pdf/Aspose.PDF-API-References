---
title: "AsposePdfAbout"
second_title: Aspose.PDF for Node.js via C++
description: "Get info about Product."
type: docs
url: /nodejs-cpp/misc/asposepdfabout/
---

_Get info about Product._

```js
function AsposePdfAbout()
```

**Return**: 

JSON object 

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **product** - Product name
* **family** - Product family
* **version** - Product version
* **releasedate** - Date release
* **producer** - Full name/producer


**CommonJS**:

```js
const AsposePdf = require('../AsposePDFforNode.cjs');
AsposePdf().then(AsposePdfModule => {
    /*AsposePdfAbout - Get info about Product*/
    const json = AsposePdfModule.AsposePdfAbout();
    /* JSON
    Product name:       json.product
    Product family:     json.family
    Product version:    json.version
    Date release:       json.releasedate
    Full name/producer: json.producer
    */
    console.log("AsposePdfAbout => %O", json.errorCode == 0 ? 'Full name/producer: ' + json.producer : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from '../AsposePDFforNode.mjs';
const AsposePdfModule = await AsposePdf();
/*AsposePdfAbout - Get info about Product*/
const json = AsposePdfModule.AsposePdfAbout();
/* JSON
Product name:       json.product
Product family:     json.family
Product version:    json.version
Date release:       json.releasedate
Full name/producer: json.producer
*/
console.log("AsposePdfAbout => %O", json.errorCode == 0 ? 'Full name/producer: ' + json.producer : json.errorText);
```