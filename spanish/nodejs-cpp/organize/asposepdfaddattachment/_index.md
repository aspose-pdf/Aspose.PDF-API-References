---
title: "AsposePdfAddAttachment"
second_title: "Aspose.PDF para Node.js via C++"
description: "Agregar adjunto a un archivo PDF."
type: docs
url: /es/nodejs-cpp/organize/asposepdfaddattachment/
---

_Agregar un adjunto a un archivo PDF._

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
Objeto JSON
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