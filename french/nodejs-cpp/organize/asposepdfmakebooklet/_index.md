---
title: "AsposePdfMakeBooklet"
second_title: "Aspose.PDF pour Node.js via C++"
description: "Créer un livret à partir d'un fichier PDF."
type: docs
url: /fr/nodejs-cpp/organize/asposepdfmakebooklet/
---

_Créer un livret à partir d'un PDF-file._

```js
function AsposePdfMakeBooklet(
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
    /*Make booklet from a PDF-file and save the "ResultMakeBooklet.pdf"*/
    const json = AsposePdfModule.AsposePdfMakeBooklet(pdf_file, "ResultMakeBooklet.pdf");
    console.log("AsposePdfMakeBooklet => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Make booklet from a PDF-file and save the "ResultMakeBooklet.pdf"*/
const json = AsposePdfModule.AsposePdfMakeBooklet(pdf_file, "ResultMakeBooklet.pdf");
console.log("AsposePdfMakeBooklet => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```