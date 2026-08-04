---
title: "AsposePdfToXps"
second_title: "Aspose.PDF pour Node.js via C++"
description: "Convertir un fichier PDF en Xps."
type: docs
url: /fr/nodejs-cpp/convert/asposepdftoxps/
---

_Convertir un fichier PDF en Xps._

```js
function AsposePdfToXps(
    fileName,
    fileNameResult 
)
```

**Parameters**: 

* **fileName** file name 
* **fileNameResult** result file name 

**Return**: 
Objet JSON
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Convert a PDF-file to Xps and save the "ResultPDFtoXps.xps"*/
    const json = AsposePdfModule.AsposePdfToXps(pdf_file, "ResultPDFtoXps.xps");
    console.log("AsposePdfToXps => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Convert a PDF-file to Xps and save the "ResultPDFtoXps.xps"*/
const json = AsposePdfModule.AsposePdfToXps(pdf_file, "ResultPDFtoXps.xps");
console.log("AsposePdfToXps => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```