---
title: "AsposePdfAConvertToPDF"
second_title: "Aspose.PDF için Node.js üzerinden C++."
description: "PDF/A dosyasını PDF'ye dönüştür."
type: docs
url: /tr/nodejs-cpp/convert/asposepdfaconverttopdf/
---

_PDF/A dosyasını PDF formatına dönüştür._

```js
function AsposePdfAConvertToPDF(
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
const pdf_PDFA_file = 'ResultConvertToPDFA.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Convert a PDF/A-file to PDF and save the "ResultConvertToPDF.pdf"*/
    const json = AsposePdfModule.AsposePdfAConvertToPDF(pdf_PDFA_file, "ResultConvertToPDF.pdf");
    console.log("AsposePdfAConvertToPDF => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_PDFA_file = 'ResultConvertToPDFA.pdf';
/*Convert a PDF/A-file to PDF and save the "ResultConvertToPDF.pdf"*/
const json = AsposePdfModule.AsposePdfAConvertToPDF(pdf_PDFA_file, "ResultConvertToPDF.pdf");
console.log("AsposePdfAConvertToPDF => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```