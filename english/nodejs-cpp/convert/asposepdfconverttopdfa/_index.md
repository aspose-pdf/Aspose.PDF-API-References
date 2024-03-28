---
title: "AsposePdfConvertToPDFA"
second_title: Aspose.PDF for Node.js via C++
description:  "Convert a PDF-file to PDF/A."
type: docs
url: /nodejs-cpp/convert/asposepdfconverttopdfa/
---

_Convert a PDF-file to PDF/A._

```js
function AsposePdfConvertToPDFA(
    fileName,
    pdfFormat,
    fileNameResult,
    fileNameLogResult
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
* **fileNameResult** result file name
* **fileNameLogResult** result Log (xml) file name

**Return**: 
JSON object 
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **fileNameResult** - result file name
  * **fileNameLogResult** - result Log (xml) file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Convert a PDF-file to PDF/A(1A) and save the "ResultConvertToPDFA.pdf"*/
    /*During conversion process, the validation is also performed, "ResultConvertToPDFA.xml"*/
    const json = AsposePdfModule.AsposePdfConvertToPDFA(pdf_file, AsposePdfModule.PdfFormat.PDF_A_1A, "ResultConvertToPDFA.pdf", "ResultConvertToPDFALog.xml");
    console.log("AsposePdfConvertToPDFA => %O", json.errorCode == 0 ? [json.fileNameResult, json.fileNameLogResult] : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Convert a PDF-file to PDF/A(1A) and save the "ResultConvertToPDFA.pdf"*/
/*During conversion process, the validation is also performed, "ResultConvertToPDFA.xml"*/
const json = AsposePdfModule.AsposePdfConvertToPDFA(pdf_file, AsposePdfModule.PdfFormat.PDF_A_1A, "ResultConvertToPDFA.pdf", "ResultConvertToPDFALog.xml");
console.log("AsposePdfConvertToPDFA => %O", json.errorCode == 0 ? [json.fileNameResult, json.fileNameLogResult] : json.errorText);
```