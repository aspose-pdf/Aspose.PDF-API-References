---
title: "AsposePdfRemoveMetadata"
second_title: "Aspose.PDF for Node.js via C++"
description: "Удалить метаданные из PDF‑файла."
type: docs
url: /ru/nodejs-cpp/metadata/asposepdfremovemetadata/
---

_Удалить метаданные из PDF‑файла._

```js
function AsposePdfRemoveMetadata(
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
    /*Remove metadata from a PDF-file and save the "ResultPdfRemoveMetadata.pdf"*/
    const json = AsposePdfModule.AsposePdfRemoveMetadata(pdf_file, "ResultPdfRemoveMetadata.pdf");
    console.log("AsposePdfRemoveMetadata => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Remove metadata from a PDF-file and save the "ResultPdfRemoveMetadata.pdf"*/
const json = AsposePdfModule.AsposePdfRemoveMetadata(pdf_file, "ResultPdfRemoveMetadata.pdf");
console.log("AsposePdfRemoveMetadata => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```