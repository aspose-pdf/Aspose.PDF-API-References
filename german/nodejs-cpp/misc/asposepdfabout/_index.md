---
title: "AsposePdfAbout"
second_title: "Aspose.PDF für Node.js via C++"
description: "Rufen Sie Informationen über das Produkt ab."
type: docs
url: /de/nodejs-cpp/misc/asposepdfabout/
---

_Informationen über das Produkt erhalten._

```js
function AsposePdfAbout()
```

**Return**: 

JSON-Objekt

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