---
title: "AsposePdfAddAttachment"
second_title: "Aspose.PDF 用于 Node.js via C++"
description: "向 PDF 文件添加附件。"
type: docs
url: /zh/nodejs-cpp/organize/asposepdfaddattachment/
---

_向 PDF 文件添加附件._

```js
function AsposePdfAddAttachment(
    fileName,
    fileAttachment,
    fileDescription,
    fileNameResult 
)
```

**Parameters**: 

* **fileName** file name
* **fileAttachment** attachment file name
* **fileDescription** attachment description
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
const txt_file = 'ReadMe.txt';
AsposePdf().then(AsposePdfModule => {
    /*Add attachment to a PDF-file and save the "ResultPdfAddAttachment.pdf"*/
    const json = AsposePdfModule.AsposePdfAddAttachment(pdf_file, txt_file, 'Description', "ResultPdfAddAttachment.pdf");
    console.log("AsposePdfAddAttachment => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
const txt_file = 'ReadMe.txt';
/*Add attachment to a PDF-file and save the "ResultPdfAddAttachment.pdf"*/
const json = AsposePdfModule.AsposePdfAddAttachment(pdf_file, txt_file, 'Description', "ResultPdfAddAttachment.pdf");
console.log("AsposePdfAddAttachment => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```