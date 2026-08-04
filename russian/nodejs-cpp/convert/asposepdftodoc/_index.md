---
title: "AsposePdfToDoc"
second_title: "Aspose.PDF for Node.js via C++"
description: "Конвертировать PDF-файл в Doc."
type: docs
url: /ru/nodejs-cpp/convert/asposepdftodoc/
---

_Преобразовать PDF‑файл в Doc._

```js
function AsposePdfToDoc(
    fileName,
    fileNameResult 
)
```

**Parameters**: 

* **fileName** file name 
* **fileNameResult** result file name 

**Return**: 
Объект JSON
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Convert a PDF-file to Doc and save the "ResultPDFtoDoc.doc"*/
    const json = AsposePdfModule.AsposePdfToDoc(pdf_file, "ResultPDFtoDoc.doc");
    console.log("AsposePdfToDoc => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Convert a PDF-file to Doc and save the "ResultPDFtoDoc.doc"*/
const json = AsposePdfModule.AsposePdfToDoc(pdf_file, "ResultPDFtoDoc.doc");
console.log("AsposePdfToDoc => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```