---
title: "AsposePdfDeleteHiddenText"
second_title: "Aspose.PDF für Node.js via C++"
description: "Versteckten Text aus einer PDF-Datei löschen."
type: docs
url: /de/nodejs-cpp/organize/asposepdfdeletehiddentext/
---

_Versteckten Text aus einer PDF-Datei löschen._

```js
function AsposePdfDeleteHiddenText(
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
    /*Delete hidden text from a PDF-file and save the "ResultPdfDeleteHiddenText.pdf"*/
    const json = AsposePdfModule.AsposePdfDeleteHiddenText(pdf_file, "ResultPdfDeleteHiddenText.pdf");
    console.log("AsposePdfDeleteHiddenText => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Delete hidden text from a PDF-file and save the "ResultPdfDeleteHiddenText.pdf"*/
const json = AsposePdfModule.AsposePdfDeleteHiddenText(pdf_file, "ResultPdfDeleteHiddenText.pdf");
console.log("AsposePdfDeleteHiddenText => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```