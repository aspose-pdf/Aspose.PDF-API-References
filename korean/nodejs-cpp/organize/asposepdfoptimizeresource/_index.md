---
title: "AsposePdfOptimizeResource"
second_title: "C++를 통해 Node.js용 Aspose.PDF"
description: "PDF 파일의 리소스를 최적화합니다."
type: docs
url: /ko/nodejs-cpp/organize/asposepdfoptimizeresource/
---

_PDF 파일의 리소스를 최적화합니다._

```js
function AsposePdfOptimizeResource(
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
    /*Optimize resources of PDF-file and save the "ResultPdfOptimizeResource.pdf"*/
    const json = AsposePdfModule.AsposePdfOptimizeResource(pdf_file, "ResultPdfOptimizeResource.pdf");
    console.log("AsposePdfOptimizeResource => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Optimize resources of PDF-file and save the "ResultPdfOptimizeResource.pdf"*/
const json = AsposePdfModule.AsposePdfOptimizeResource(pdf_file, "ResultPdfOptimizeResource.pdf");
console.log("AsposePdfOptimizeResource => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```