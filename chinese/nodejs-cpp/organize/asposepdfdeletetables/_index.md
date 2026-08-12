---
title: "AsposePdfDeleteTables"
second_title: "Aspose.PDF 用于 Node.js via C++"
description: "从 PDF 文件中删除表格。"
type: docs
url: /zh/nodejs-cpp/organize/asposepdfdeletetables/
---

_删除 PDF 文件中的表格。_

```js
function AsposePdfDeleteTables(
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
    /*Delete tables from a PDF-file and save the "ResultPdfDeleteTables.pdf"*/
    const json = AsposePdfModule.AsposePdfDeleteTables(pdf_file, "ResultPdfDeleteTables.pdf");
    console.log("AsposePdfDeleteTables => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Delete tables from a PDF-file and save the "ResultPdfDeleteTables.pdf"*/
const json = AsposePdfModule.AsposePdfDeleteTables(pdf_file, "ResultPdfDeleteTables.pdf");
console.log("AsposePdfDeleteTables => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```