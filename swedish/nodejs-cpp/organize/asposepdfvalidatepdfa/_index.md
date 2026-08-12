---
title: "AsposePdfValidatePDFA"
second_title: "Aspose.PDF för Node.js via C++"
description: "Validera PDF/A-kompatibilitet för en PDF-fil."
type: docs
url: /sv/nodejs-cpp/organize/asposepdfvalidatepdfa/
---

_Validera PDF/A-kompatibilitet för en PDF-fil._

```js
function AsposePdfValidatePDFA(
    fileName,
    pdfFormat,
    fileNameResult 
)
```

**Parameters**: 

* **fileName** file name 
* **pdfFormat** format PDF/A:
  * Module.PdfFormat.PDF_A_1A
  * Module.PdfFormat.PDF_A_1B
  * Module.PdfFormat.PDF_A_2A
  * Module.PdfFormat.PDF_A_3A
  * Module.PdfFormat.PDF_A_2U
  * Module.PdfFormat.PDF_A_3B
  * Module.PdfFormat.PDF_A_3U
* **fileNameResult** result file name where verification comments will be stored (xml format)

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
    /*Validate PDF/A compatibility a PDF-file and save result in the "ResultPdfValidatePDFA.xml"*/
    const json = AsposePdfModule.AsposePdfValidatePDFA(pdf_file, AsposePdfModule.PdfFormat.PDF_A_1A, "ResultPdfValidatePDFA.xml");
    console.log("AsposePdfValidatePDFA => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Validate PDF/A compatibility a PDF-file and save result in the "ResultPdfValidatePDFA.xml"*/
const json = AsposePdfModule.AsposePdfValidatePDFA(pdf_file, AsposePdfModule.PdfFormat.PDF_A_1A, "ResultPdfValidatePDFA.xml");
console.log("AsposePdfValidatePDFA => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```