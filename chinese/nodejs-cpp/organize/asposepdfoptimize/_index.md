---
title: "AsposePdfOptimize"
second_title: "Aspose.PDF 用于 Node.js via C++"
description: "优化 PDF 文件。"
type: docs
url: /zh/nodejs-cpp/organize/asposepdfoptimize/
---

_优化 PDF 文件。_

```js
function AsposePdfOptimize(
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
    /*Optimize a PDF-file and save the "ResultOptimize.pdf"*/
    const json = AsposePdfModule.AsposePdfOptimize(pdf_file, "ResultOptimize.pdf");
    console.log("AsposePdfOptimize => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Optimize a PDF-file and save the "ResultOptimize.pdf"*/
const json = AsposePdfModule.AsposePdfOptimize(pdf_file, "ResultOptimize.pdf");
console.log("AsposePdfOptimize => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```