---
title: "AsposePdfCropPages"
second_title: Aspose.PDF for Node.js via C++
description:  "Crop PDF-pages."
type: docs
url: /nodejs-cpp/organize/asposepdfcroppages/
---

_Crop PDF-pages._

```js
function AsposePdfCropPages(
    fileName,
    margin,
    fileNameResult 
)
```

**Parameters**: 

* **fileName** file name 
* **margin** page margin
* **fileNameResult** result file name 

**Return**: 
JSON object 
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    const margin = 1.5;
    /*Crop PDF-pages and save the "ResultPdfCropPages.pdf"*/
    const json = AsposePdfModule.AsposePdfCropPages(pdf_file, margin, "ResultPdfCropPages.pdf");
    console.log("AsposePdfCropPages => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
const margin = 1.5;
/*Crop PDF-pages and save the "ResultPdfCropPages.pdf"*/
const json = AsposePdfModule.AsposePdfCropPages(pdf_file, margin, "ResultPdfCropPages.pdf");
console.log("AsposePdfCropPages => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```