---
title: "AsposePdfRemoveMetadata"
second_title: "C++를 통해 Node.js용 Aspose.PDF"
description: "PDF 파일에서 메타데이터를 제거합니다."
type: docs
url: /ko/nodejs-cpp/metadata/asposepdfremovemetadata/
---

_PDF 파일에서 메타데이터를 제거합니다._

```js
function AsposePdfRemoveMetadata(
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
    /*Remove metadata from a PDF-file and save the "ResultPdfRemoveMetadata.pdf"*/
    const json = AsposePdfModule.AsposePdfRemoveMetadata(pdf_file, "ResultPdfRemoveMetadata.pdf");
    console.log("AsposePdfRemoveMetadata => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Remove metadata from a PDF-file and save the "ResultPdfRemoveMetadata.pdf"*/
const json = AsposePdfModule.AsposePdfRemoveMetadata(pdf_file, "ResultPdfRemoveMetadata.pdf");
console.log("AsposePdfRemoveMetadata => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```