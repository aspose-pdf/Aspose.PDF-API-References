---
title: "AsposePdfMakeNUp"
second_title: "Aspose.PDF pour Node.js via C++"
description: "Créer un document N‑Up à partir d'un fichier PDF."
type: docs
url: /fr/nodejs-cpp/organize/asposepdfmakenup/
---

_Créer un document N-Up à partir d'un PDF-file._

```js
function AsposePdfMakeNUp(
    fileName,
    columns,
    rows,
    fileNameResult 
)
```

**Parameters**: 

* **fileName** file name 
* **columns** count of columns
* **rows** count of rows
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
    const columns = 2
    const rows = 2
    /*Make N-Up document from a PDF-file and save the "ResultMakeNUp.pdf"*/
    const json = AsposePdfModule.AsposePdfMakeNUp(pdf_file, columns, rows, "ResultMakeNUp.pdf");
    console.log("AsposePdfMakeNUp => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
const columns = 2
const rows = 2
/*Make N-Up document from a PDF-file and save the "ResultMakeNUp.pdf"*/
const json = AsposePdfModule.AsposePdfMakeNUp(pdf_file, columns, rows, "ResultMakeNUp.pdf");
console.log("AsposePdfMakeNUp => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```