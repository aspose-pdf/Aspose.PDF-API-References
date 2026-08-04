---
title: "AsposePdfDeleteWatermarks"
second_title: "C++를 통해 Node.js용 Aspose.PDF"
description: "PDF 파일에서 워터마크를 삭제합니다."
type: docs
url: /ko/nodejs-cpp/organize/asposepdfdeletewatermarks/
---

_PDF 파일에서 워터마크를 삭제합니다._

```js
function AsposePdfDeleteWatermarks(
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
  * **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Delete watermarks from a PDF-file and save the "ResultPdfDeleteWatermarks.pdf"*/
    const json = AsposePdfModule.AsposePdfDeleteWatermarks(pdf_file, "ResultPdfDeleteWatermarks.pdf");
    console.log("AsposePdfDeleteWatermarks => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Delete watermarks from a PDF-file and save the "ResultPdfDeleteWatermarks.pdf"*/
const json = AsposePdfModule.AsposePdfDeleteWatermarks(pdf_file, "ResultPdfDeleteWatermarks.pdf");
console.log("AsposePdfDeleteWatermarks => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```