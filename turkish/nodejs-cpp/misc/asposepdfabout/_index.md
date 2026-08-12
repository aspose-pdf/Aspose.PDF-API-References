---
title: "AsposePdfAbout"
second_title: "Aspose.PDF için Node.js üzerinden C++."
description: "Ürün hakkında bilgi al."
type: docs
url: /tr/nodejs-cpp/misc/asposepdfabout/
---

_Ürün hakkında bilgi al._

```js
function AsposePdfAbout()
```

**Return**: 

JSON nesnesi

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **product** - Product name
* **family** - Product family
* **version** - Product version
* **releasedate** - Date release
* **producer** - Full name/producer
* **islicensed** - Product is licensed


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
AsposePdf().then(AsposePdfModule => {
    /*AsposePdfAbout - Get info about Product*/
    const json = AsposePdfModule.AsposePdfAbout();
    /* JSON
    Product name       : json.product
    Product family     : json.family
    Product version    : json.version
    Date release       : json.releasedate
    Full name/producer : json.producer
    Product is licensed: json.islicensed
    */
    console.log("AsposePdfAbout => %O", json.errorCode == 0 ? 'Full name/producer: ' + json.producer : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
/*AsposePdfAbout - Get info about Product*/
const json = AsposePdfModule.AsposePdfAbout();
/* JSON
    Product name       : json.product
    Product family     : json.family
    Product version    : json.version
    Date release       : json.releasedate
    Full name/producer : json.producer
    Product is licensed: json.islicensed
*/
console.log("AsposePdfAbout => %O", json.errorCode == 0 ? 'Full name/producer: ' + json.producer : json.errorText);
```