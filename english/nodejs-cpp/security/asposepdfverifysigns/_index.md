---
title: "AsposePdfVerifySigns"
second_title: Aspose.PDF for Node.js via C++
description:  "Verify the validity of digital signatures in a PDF-file."
type: docs
url: /nodejs-cpp/security/asposepdfverifysigns/
---

_Verify the validity of digital signatures in a PDF-file._

```js
function AsposePdfVerifySigns(
    fileName
)
```

**Parameters**: 

* **fileName** file name 

**Return**:

JSON object

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **signs** - array of : 
  * signName - sign name
  * signStatus - status of sign : "VALID"|"INVALID"|"INACTIVE"


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Verify the validity of digital signatures in a PDF-file*/
    const json = AsposePdfModule.AsposePdfVerifySigns(pdf_file);
    /*json.signs - array of signs: { signName: <string>, signStatus: <string {"VALID"|"INVALID"|"INACTIVE"}> }*/
    console.log("AsposePdfVerifySigns => signs: %O", json.errorCode == 0 ? json.signs : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Verify the validity of digital signatures in a PDF-file*/
const json = AsposePdfModule.AsposePdfVerifySigns(pdf_file);
/*json.signs - array of signs: { signName: <string>, signStatus: <string {"VALID"|"INVALID"|"INACTIVE"}> }*/
console.log("AsposePdfVerifySigns => signs: %O", json.errorCode == 0 ? json.signs : json.errorText);
```