---
title: "AsposePdfToEPUB"
second_title: "Aspose.PDF para Node.js via C++"
description: "Converter um arquivo PDF para ePub."
type: docs
url: /pt/nodejs-cpp/convert/asposepdftoepub/
---

_Converter um arquivo PDF para ePub._

```js
function AsposePdfToEPUB(
    fileName,
    fileNameResult 
)
```

**Parameters**: 

* **fileName** file name 
* **fileNameResult** result file name 

**Return**: 
Objeto JSON
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Convert a PDF-file to ePub and save the "ResultPDFtoEPUB.epub"*/
    const json = AsposePdfModule.AsposePdfToEPUB(pdf_file, "ResultPDFtoEPUB.epub");
    console.log("AsposePdfToEPUB => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Convert a PDF-file to ePub and save the "ResultPDFtoEPUB.epub"*/
const json = AsposePdfModule.AsposePdfToEPUB(pdf_file, "ResultPDFtoEPUB.epub");
console.log("AsposePdfToEPUB => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```