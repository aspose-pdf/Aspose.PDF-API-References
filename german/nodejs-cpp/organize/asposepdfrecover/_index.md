---
title: "AsposePdfRecover"
second_title: "Aspose.PDF für Node.js via C++"
description: "Stellen Sie die Struktur einer PDF-Datei wieder her und entfernen Sie ungültige Daten."
type: docs
url: /de/nodejs-cpp/organize/asposepdfrecover/
---

_Stellen Sie die Struktur einer PDF-Datei wieder her und entfernen Sie ungültige Daten._

```js
function AsposePdfRecover(
    fileName,
    fileNameResult
)
```

**Parameters**: 

* **fileName** file name 
* **fileNameResult** result file name 

**Return**: 
JSON-Objekt
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Recover a PDF-file structure and trims invalid data and save the "ResultPdfRecover.pdf"*/
    const json = AsposePdfModule.AsposePdfRecover(pdf_file, "ResultPdfRecover.pdf");
    console.log("AsposePdfRecover => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Recover a PDF-file structure and trims invalid data and save the "ResultPdfRecover.pdf"*/
const json = AsposePdfModule.AsposePdfRecover(pdf_file, "ResultPdfRecover.pdf");
console.log("AsposePdfRecover => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```