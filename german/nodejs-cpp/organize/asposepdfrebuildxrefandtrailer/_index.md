---
title: "AsposePdfRebuildXrefAndTrailer"
second_title: "Aspose.PDF für Node.js via C++"
description: "Erstellen Sie die Kreuzreferenztabelle und Trailer-Strukturen einer PDF-Datei neu."
type: docs
url: /de/nodejs-cpp/organize/asposepdfrebuildxrefandtrailer/
---

_Cross-Reference-Tabelle und Trailer-Strukturen einer PDF-Datei neu aufbauen._

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
JSON-Objekt
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