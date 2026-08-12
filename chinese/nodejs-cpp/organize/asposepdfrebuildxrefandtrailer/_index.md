---
title: "AsposePdfRebuildXrefAndTrailer"
second_title: "Aspose.PDF 用于 Node.js via C++"
description: "重建 PDF 文件的交叉引用表和尾部结构。"
type: docs
url: /zh/nodejs-cpp/organize/asposepdfrebuildxrefandtrailer/
---

_重建 PDF 文件的交叉引用表和尾部结构。_

```js
function AsposePdfRebuildXrefAndTrailer(
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
    /*Rebuild a PDF-file cross-reference table and trailer structures and save the "ResultPdfRebuildXrefAndTrailer.pdf"*/
    const json = AsposePdfModule.AsposePdfRebuildXrefAndTrailer(pdf_file, "ResultPdfRebuildXrefAndTrailer.pdf");
    console.log("AsposePdfRebuildXrefAndTrailer => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Rebuild a PDF-file cross-reference table and trailer structures and save the "ResultPdfRebuildXrefAndTrailer.pdf"*/
const json = AsposePdfModule.AsposePdfRebuildXrefAndTrailer(pdf_file, "ResultPdfRebuildXrefAndTrailer.pdf");
console.log("AsposePdfRebuildXrefAndTrailer => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```