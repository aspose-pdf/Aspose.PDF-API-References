---
title: "AsposePdfDeleteTextFooters"
second_title: "Aspose.PDF para Node.js via C++"
description: "Eliminar pies de página de texto de un archivo PDF."
type: docs
url: /es/nodejs-cpp/organize/asposepdfdeletetextfooters/
---

_Eliminar pies de texto de un archivo PDF._

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
Objeto JSON
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