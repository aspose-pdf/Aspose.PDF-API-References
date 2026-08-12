---
title: "AsposePdfUnembedFonts"
second_title: "Aspose.PDF pour Node.js via C++"
description: "Désincorporer les polices d'un fichier PDF."
type: docs
url: /fr/nodejs-cpp/organize/asposepdfunembedfonts/
---

_Désintégrer les polices d'un PDF-file._

```js
function AsposePdfUnembedFonts(
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
    /*Unembed fonts a PDF-file and save the "ResultUnembedFonts.pdf"*/
    const json = AsposePdfModule.AsposePdfUnembedFonts(pdf_file, "ResultUnembedFonts.pdf");
    console.log("AsposePdfUnembedFonts => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Unembed fonts a PDF-file and save the "ResultUnembedFonts.pdf"*/
const json = AsposePdfModule.AsposePdfUnembedFonts(pdf_file, "ResultUnembedFonts.pdf");
console.log("AsposePdfUnembedFonts => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```