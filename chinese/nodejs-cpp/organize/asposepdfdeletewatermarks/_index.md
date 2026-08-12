---
title: "AsposePdfDeleteWatermarks"
second_title: "Aspose.PDF 用于 Node.js via C++"
description: "从 PDF 文件中删除水印。"
type: docs
url: /zh/nodejs-cpp/organize/asposepdfdeletewatermarks/
---

_删除 PDF 文件中的水印._

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
JSON 对象
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