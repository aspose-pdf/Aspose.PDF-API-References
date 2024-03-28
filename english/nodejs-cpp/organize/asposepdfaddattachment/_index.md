---
title: "AsposePdfAddAttachment"
second_title: Aspose.PDF for Node.js via C++
description: "Add attachment to a PDF-file."
type: docs
url: /nodejs-cpp/organize/asposepdfaddattachment/
---

_Add attachment to a PDF-file._

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
JSON object 
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