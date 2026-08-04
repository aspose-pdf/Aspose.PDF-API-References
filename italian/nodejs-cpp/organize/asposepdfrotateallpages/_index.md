---
title: "AsposePdfRotateAllPages"
second_title: "Aspose.PDF per Node.js via C++"
description: "Ruota le pagine PDF."
type: docs
url: /it/nodejs-cpp/organize/asposepdfrotateallpages/
---

_Ruota le pagine PDF._

```js
function AsposePdfRotateAllPages(
    fileName,
    rotation,
    fileNameResult 
)
```

**Parameters**: 

* **fileName** file name 
* **rotation** pages rotation:
  * Module.Rotation.None
  * Module.Rotation.on90
  * Module.Rotation.on180
  * Module.Rotation.on270 
* **fileNameResult** result file name 

**Return**: 
Oggetto JSON
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Rotate PDF-pages and save the "ResultRotation.pdf"*/
    const json = AsposePdfModule.AsposePdfRotateAllPages(pdf_file, AsposePdfModule.Rotation.on270, "ResultRotation.pdf");
    console.log("AsposePdfRotateAllPages => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Rotate PDF-pages and save the "ResultRotation.pdf"*/
const json = AsposePdfModule.AsposePdfRotateAllPages(pdf_file, AsposePdfModule.Rotation.on270, "ResultRotation.pdf");
console.log("AsposePdfRotateAllPages => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```