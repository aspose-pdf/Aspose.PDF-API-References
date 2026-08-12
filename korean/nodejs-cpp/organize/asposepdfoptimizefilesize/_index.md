---
title: "AsposePdfOptimizeFileSize"
second_title: "C++를 통해 Node.js용 Aspose.PDF"
description: "이미지 압축 품질로 PDF 파일의 크기를 최적화합니다."
type: docs
url: /ko/nodejs-cpp/organize/asposepdfoptimizefilesize/
---

_이미지 압축 품질로 PDF 파일의 크기를 최적화합니다._

```js
function AsposePdfOptimizeFileSize(
    fileName,
    imageQuality,
    fileNameResult 
)
```

**Parameters**: 

* **fileName** file name 
* **imageQuality** image compression quality
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
    const imageQuality = 50;
    /*Optimize size of PDF-file with image compression quality and save the "ResultPdfOptimizeFileSize.pdf"*/
    const json = AsposePdfModule.AsposePdfOptimizeFileSize(pdf_file, imageQuality, "ResultPdfOptimizeFileSize.pdf");
    console.log("AsposePdfOptimizeFileSize => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
const imageQuality = 50;
/*Optimize size of PDF-file with image compression quality and save the "ResultPdfOptimizeFileSize.pdf"*/
const json = AsposePdfModule.AsposePdfOptimizeFileSize(pdf_file, imageQuality, "ResultPdfOptimizeFileSize.pdf");
console.log("AsposePdfOptimizeFileSize => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```