---
title: "AsposePdfFlatten"
second_title: "Aspose.PDF için Node.js üzerinden C++."
description: "PDF-file'ı düzleştir."
type: docs
url: /tr/nodejs-cpp/organize/asposepdfflatten/
---

_PDF dosyasını düzleştir._

```js
function AsposePdfFlatten(
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
    /*Flatten a PDF-file and save the "ResultFlatten.pdf"*/
    const json = AsposePdfModule.AsposePdfFlatten(pdf_file, "ResultFlatten.pdf");
    console.log("AsposePdfFlatten => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Flatten a PDF-file and save the "ResultFlatten.pdf"*/
const json = AsposePdfModule.AsposePdfFlatten(pdf_file, "ResultFlatten.pdf");
console.log("AsposePdfFlatten => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```