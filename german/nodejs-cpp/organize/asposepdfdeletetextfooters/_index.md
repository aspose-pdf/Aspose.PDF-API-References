---
title: "AsposePdfDeleteTextFooters"
second_title: "Aspose.PDF für Node.js via C++"
description: "Textfußzeilen aus einer PDF-Datei löschen."
type: docs
url: /de/nodejs-cpp/organize/asposepdfdeletetextfooters/
---

_Textfußzeilen aus einer PDF‑Datei entfernen._

```js
function AsposePdfDeleteTextFooters(
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
    /*Delete text footers from a PDF-file and save the "ResultPdfDeleteTextFooters.pdf"*/
    const json = AsposePdfModule.AsposePdfDeleteTextFooters(pdf_file, "ResultPdfDeleteTextFooters.pdf");
    console.log("AsposePdfDeleteTextFooters => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Delete text footers from a PDF-file and save the "ResultPdfDeleteTextFooters.pdf"*/
const json = AsposePdfModule.AsposePdfDeleteTextFooters(pdf_file, "ResultPdfDeleteTextFooters.pdf");
console.log("AsposePdfDeleteTextFooters => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```