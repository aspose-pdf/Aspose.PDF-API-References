---
title: "AsposePdfMakeNUp"
second_title: "Aspose.PDF para Node.js via C++"
description: "Criar documento N-Up a partir de um arquivo PDF."
type: docs
url: /pt/nodejs-cpp/organize/asposepdfmakenup/
---

_Crie um documento N-Up a partir de um arquivo PDF._

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
Objeto JSON
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