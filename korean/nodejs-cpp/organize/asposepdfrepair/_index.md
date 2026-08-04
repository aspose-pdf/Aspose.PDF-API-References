---
title: "AsposePdfRepair"
second_title: "C++를 통해 Node.js용 Aspose.PDF"
description: "PDF 파일을 복구합니다."
type: docs
url: /ko/nodejs-cpp/organize/asposepdfrepair/
---

_PDF 파일을 복구합니다._

```js
function AsposePdfRepair(
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
    /*Repair a PDF-file and save the "ResultPdfRepair.pdf"*/
    const json = AsposePdfModule.AsposePdfRepair(pdf_file, "ResultPdfRepair.pdf");
    console.log("AsposePdfRepair => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Repair a PDF-file and save the "ResultPdfRepair.pdf"*/
const json = AsposePdfModule.AsposePdfRepair(pdf_file, "ResultPdfRepair.pdf");
console.log("AsposePdfRepair => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```