---
title: "AsposePdfOptimizeResource"
second_title: "Aspose.PDF için Node.js üzerinden C++."
description: "PDF-file'ın kaynaklarını optimize et."
type: docs
url: /tr/nodejs-cpp/organize/asposepdfoptimizeresource/
---

_PDF-dosyasının kaynaklarını optimize et._

```js
function AsposePdfOptimizeResource(
    fileName,
    fileNameResult
)
```

**Parameters**: 

* **fileName** file name 
* **fileNameResult** result file name 

**Return**: 
JSON nesnesi
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Optimize resources of PDF-file and save the "ResultPdfOptimizeResource.pdf"*/
    const json = AsposePdfModule.AsposePdfOptimizeResource(pdf_file, "ResultPdfOptimizeResource.pdf");
    console.log("AsposePdfOptimizeResource => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Optimize resources of PDF-file and save the "ResultPdfOptimizeResource.pdf"*/
const json = AsposePdfModule.AsposePdfOptimizeResource(pdf_file, "ResultPdfOptimizeResource.pdf");
console.log("AsposePdfOptimizeResource => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```