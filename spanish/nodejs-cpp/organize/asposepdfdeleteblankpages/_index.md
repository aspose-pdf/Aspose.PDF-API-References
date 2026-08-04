---
title: "AsposePdfDeleteBlankPages"
second_title: "Aspose.PDF para Node.js via C++"
description: "Eliminar páginas en blanco de un archivo PDF."
type: docs
url: /es/nodejs-cpp/organize/asposepdfdeleteblankpages/
---

_Eliminar páginas en blanco de un archivo PDF._

```js
function AsposePdfDeleteBlankPages(
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
    /*Delete blank pages from a PDF-file and save the "ResultDeleteBlankPages.pdf"*/
    const json = AsposePdfModule.AsposePdfDeleteBlankPages(pdf_file, "ResultDeleteBlankPages.pdf");
    console.log("AsposePdfDeleteBlankPages => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Delete blank pages from a PDF-file and save the "ResultDeleteBlankPages.pdf"*/
const json = AsposePdfModule.AsposePdfDeleteBlankPages(pdf_file, "ResultDeleteBlankPages.pdf");
console.log("AsposePdfDeleteBlankPages => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```