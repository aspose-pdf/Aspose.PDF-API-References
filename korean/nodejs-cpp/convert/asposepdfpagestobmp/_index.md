---
title: "AsposePdfPagesToBmp"
second_title: "C++를 통해 Node.js용 Aspose.PDF"
description: "PDF 파일을 BMP로 변환합니다."
type: docs
url: /ko/nodejs-cpp/convert/asposepdfpagestobmp/
---

_PDF 파일을 BMP로 변환합니다._

```
function AsposePdfPagesToBmp(
    fileName,
    fileNameResult,
    resolution
)
```

**Parameters**: 
  * **fileName** file name 
  * **fileNameResult** result file name template (for sample: "ResultPdfToBmp{0:D2}.bmp" where {0}, {0:D2}, {0:D3}, {0:Dn} - format page number) 
  * **resolution** image resolution, default 300 dpi

**Return**: 
JSON 객체
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **filesCount** - bmp files count
  * **filesNameResult** - array of result filenames


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Convert a PDF-file to BMP with template "ResultPdfToBmp{0:D2}.bmp" ({0}, {0:D2}, {0:D3}, ... format page number), resolution 150 DPI and save*/
    const json = AsposePdfModule.AsposePdfPagesToBmp(pdf_file, "ResultPdfToBmp{0:D2}.bmp", 150);
    console.log("AsposePdfPagesToBmp => %O", json.errorCode == 0 ? json.filesNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Convert a PDF-file to BMP with template "ResultPdfToBmp{0:D2}.bmp" ({0}, {0:D2}, {0:D3}, ... format page number), resolution 150 DPI and save*/
const json = AsposePdfModule.AsposePdfPagesToBmp(pdf_file, "ResultPdfToBmp{0:D2}.bmp", 150);
console.log("AsposePdfPagesToBmp => %O", json.errorCode == 0 ? json.filesNameResult : json.errorText);
```