---
title: "AsposePdfPagesToPDF"
second_title: Aspose.PDF for Node.js via C++
description:  "Convert a PDF-file to PDF (separate pages)."
type: docs
url: /nodejs-cpp/convert/asposepdfpagestopdf/
---

_Convert a PDF-file to PDF (separate pages)._

```
function AsposePdfPagesToPDF(
    fileName,
    fileNameResult
)
```

**Parameters**: 
  * **fileName** file name 
  * **fileNameResult** result file name template (for sample: "ResultPdfPagesToPDF{0:D2}.pdf" where {0}, {0:D2}, {0:D3}, {0:Dn} - format page number) 

**Return**: 
JSON object 
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **filesCount** - result files count
  * **filesNameResult** - array of result filenames


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Convert a PDF-file to separate PDF pages with template "ResultPdfToPDF{0:D2}.pdf" ({0}, {0:D2}, {0:D3}, ... format page number) and save*/
    const json = AsposePdfModule.AsposePdfPagesToPDF(pdf_file, "ResultPdfToPDF{0:D2}.pdf");
    console.log("AsposePdfPagesToPDF => %O", json.errorCode == 0 ? json.filesNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Convert a PDF-file to separate PDF pages with template "ResultPdfToPDF{0:D2}.pdf" ({0}, {0:D2}, {0:D3}, ... format page number) and save*/
const json = AsposePdfModule.AsposePdfPagesToPDF(pdf_file, "ResultPdfToPDF{0:D2}.pdf");
console.log("AsposePdfPagesToPDF => %O", json.errorCode == 0 ? json.filesNameResult : json.errorText);
```