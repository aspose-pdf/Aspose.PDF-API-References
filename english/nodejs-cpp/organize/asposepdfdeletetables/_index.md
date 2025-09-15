---
title: "AsposePdfDeleteTables"
second_title: Aspose.PDF for Node.js via C++
description:  "Delete tables from a PDF-file."
type: docs
url: /nodejs-cpp/organize/asposepdfdeletetables/
---

_Delete tables from a PDF-file._

```js
function AsposePdfDeleteTables(
    fileName,
    fileNameResult
)
```

**Parameters**: 

* **fileName** file name 
* **fileNameResult** result file name 

**Return**: 
JSON object 
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Delete tables from a PDF-file and save the "ResultPdfDeleteTables.pdf"*/
    const json = AsposePdfModule.AsposePdfDeleteTables(pdf_file, "ResultPdfDeleteTables.pdf");
    console.log("AsposePdfDeleteTables => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Delete tables from a PDF-file and save the "ResultPdfDeleteTables.pdf"*/
const json = AsposePdfModule.AsposePdfDeleteTables(pdf_file, "ResultPdfDeleteTables.pdf");
console.log("AsposePdfDeleteTables => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```