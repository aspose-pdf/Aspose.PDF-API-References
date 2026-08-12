---
title: "AsposePdfToPptX"
second_title: "Aspose.PDF için Node.js üzerinden C++."
description: "PDF dosyasını PptX'e dönüştür."
type: docs
url: /tr/nodejs-cpp/convert/asposepdftopptx/
---

_PDF dosyasını PptX'e dönüştür._

```js
function AsposePdfToPptX(
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
    /*Convert a PDF-file to PptX and save the "ResultPDFtoPptX.pptx"*/
    const json = AsposePdfModule.AsposePdfToPptX(pdf_file, "ResultPDFtoPptX.pptx");
    console.log("AsposePdfToPptX => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Convert a PDF-file to PptX and save the "ResultPDFtoPptX.pptx"*/
const json = AsposePdfModule.AsposePdfToPptX(pdf_file, "ResultPDFtoPptX.pptx");
console.log("AsposePdfToPptX => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```