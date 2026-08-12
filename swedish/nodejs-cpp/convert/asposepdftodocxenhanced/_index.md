---
title: "AsposePdfToDocXEnhanced"
second_title: "Aspose.PDF för Node.js via C++"
description: "Konvertera en PDF-fil till DocX med förbättrat igenkänningsläge."
type: docs
url: /sv/nodejs-cpp/convert/asposepdftodocxenhanced/
---

_Konvertera en PDF-fil till DocX med förbättrat igenkänningsläge (fullt redigerbara tabeller och stycken)._

```js
function AsposePdfToDocXEnhanced(
    fileName,
    fileNameResult 
)
```

**Parameters**: 

* **fileName** file name 
* **fileNameResult** result file name 

**Return**: 
JSON-objekt
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Convert a PDF-file to DocX with Enhanced Recognition Mode (fully editable tables and paragraphs) and save the "ResultPDFtoDocXEnhanced.docx"*/
    const json = AsposePdfModule.AsposePdfToDocXEnhanced(pdf_file, "ResultPDFtoDocXEnhanced.docx");
    console.log("AsposePdfToDocXEnhanced => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Convert a PDF-file to DocX with Enhanced Recognition Mode (fully editable tables and paragraphs) and save the "ResultPDFtoDocXEnhanced.docx"*/
const json = AsposePdfModule.AsposePdfToDocXEnhanced(pdf_file, "ResultPDFtoDocXEnhanced.docx");
console.log("AsposePdfToDocXEnhanced => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```