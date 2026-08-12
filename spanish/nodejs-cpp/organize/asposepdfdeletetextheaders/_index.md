---
title: "AsposePdfDeleteTextHeaders"
second_title: "Aspose.PDF para Node.js via C++"
description: "Eliminar encabezados de texto de un archivo PDF."
type: docs
url: /es/nodejs-cpp/organize/asposepdfdeletetextheaders/
---

_Eliminar encabezados de texto de un archivo PDF._

```js
function AsposePdfDeleteTextHeaders(
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
    /*Delete text headers from a PDF-file and save the "ResultPdfDeleteTextHeaders.pdf"*/
    const json = AsposePdfModule.AsposePdfDeleteTextHeaders(pdf_file, "ResultPdfDeleteTextHeaders.pdf");
    console.log("AsposePdfDeleteTextHeaders => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Delete text headers from a PDF-file and save the "ResultPdfDeleteTextHeaders.pdf"*/
const json = AsposePdfModule.AsposePdfDeleteTextHeaders(pdf_file, "ResultPdfDeleteTextHeaders.pdf");
console.log("AsposePdfDeleteTextHeaders => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```