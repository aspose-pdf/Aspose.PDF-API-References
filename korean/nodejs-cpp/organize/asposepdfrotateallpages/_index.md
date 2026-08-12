---
title: "AsposePdfRotateAllPages"
second_title: "C++를 통해 Node.js용 Aspose.PDF"
description: "PDF 페이지를 회전합니다."
type: docs
url: /ko/nodejs-cpp/organize/asposepdfrotateallpages/
---

_PDF 페이지를 회전합니다._

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
JSON 객체
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