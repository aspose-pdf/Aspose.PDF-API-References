---
title: "AsposePdfPagesToSvgZip"
second_title: "C++를 통해 Node.js용 Aspose.PDF"
description: "PDF 파일을 SVG(zip)으로 변환합니다."
type: docs
url: /ko/nodejs-cpp/convert/asposepdfpagestosvgzip/
---

_PDF 파일을 SVG(zip)으로 변환합니다._

```
function AsposePdfPagesToSvgZip(
    fileName,
    fileNameResult
)
```

**Parameters**: 
  * **fileName** file name 
  * **fileNameResult** result file name

**Return**: 
JSON 객체
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **filesNameResult** - array of result filenames


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Convert a PDF-file to SVG(zip) and save the "ResultPdfToSvgZip.zip"*/
    const json = AsposePdfModule.AsposePdfPagesToSvgZip(pdf_file, "ResultPdfToSvgZip.zip");
    console.log("AsposePdfPagesToSvgZip => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*convert a PDF-file to SVG zip and save the "ResultPdfToSvgZip.zip"*/
const json = AsposePdfModule.AsposePdfPagesToSvgZip(pdf_file, "ResultPdfToSvgZip.zip");
console.log("AsposePdfPagesToSvgZip => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText)
```