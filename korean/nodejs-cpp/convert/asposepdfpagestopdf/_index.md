---
title: "AsposePdfPagesToPDF"
second_title: "C++를 통해 Node.js용 Aspose.PDF"
description: "PDF 파일을 PDF(개별 페이지)로 변환합니다."
type: docs
url: /ko/nodejs-cpp/convert/asposepdfpagestopdf/
---

_PDF 파일을 PDF(별도 페이지)로 변환합니다._

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
JSON 객체
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