---
title: "AsposePdfGetAttachment"
second_title: "Aspose.PDF für Node.js via C++"
description: "Anhang aus einer PDF-Datei abrufen."
type: docs
url: /de/nodejs-cpp/organize/asposepdfgetattachment/
---

_Anhang aus einer PDF-Datei abrufen._

```js
function AsposePdfGetAttachment(
    fileName,
    fileNameResult
)
```

**Parameters**: 
  * **fileName** file name 
  * **fileNameResult** result file name template (for sample: "ResultPdfGetAttachment_{0}" where {0} - name of attachment) 

**Return**: 
JSON-Objekt
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **filesCount** - attachment files count
  * **filesNameResult** - array of result filenames


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Get attachment from a PDF-file and save with template "ResultPdfGetAttachment_{0}" ({0} - name of attachment)*/
    const json = AsposePdfModule.AsposePdfGetAttachment(pdf_file, "ResultPdfGetAttachment_{0}");
    console.log("AsposePdfGetAttachment => %O", json.errorCode == 0 ? json.filesNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Get attachment from a PDF-file and save with template "ResultPdfGetAttachment_{0}" ({0} - name of attachment)*/
const json = AsposePdfModule.AsposePdfGetAttachment(pdf_file, "ResultPdfGetAttachment_{0}");
console.log("AsposePdfGetAttachment => %O", json.errorCode == 0 ? json.filesNameResult : json.errorText);
```