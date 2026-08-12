---
title: "AsposePdfToDocXEnhanced"
second_title: "Aspose.PDF 用于 Node.js via C++"
description: "将 PDF 文件转换为带增强识别模式的 DocX。"
type: docs
url: /zh/nodejs-cpp/convert/asposepdftodocxenhanced/
---

_将 PDF 文件转换为 DocX，使用增强识别模式（完全可编辑的表格和段落）。_

```js
function AsposePdfToDocXEnhanced(
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
    /*Convert a PDF-file to DocX with Enhanced Recognition Mode (fully editable tables and paragraphs) and save the "ResultPDFtoDocXEnhanced.docx"*/
    const json = AsposePdfModule.AsposePdfToDocXEnhanced(pdf_file, "ResultPDFtoDocXEnhanced.docx");
    console.log("AsposePdfToDocXEnhanced => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Convert a PDF-file to DocX with Enhanced Recognition Mode (fully editable tables and paragraphs) and save the "ResultPDFtoDocXEnhanced.docx"*/
const json = AsposePdfModule.AsposePdfToDocXEnhanced(pdf_file, "ResultPDFtoDocXEnhanced.docx");
console.log("AsposePdfToDocXEnhanced => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```