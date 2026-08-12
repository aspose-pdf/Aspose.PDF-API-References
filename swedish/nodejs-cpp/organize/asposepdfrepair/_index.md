---
title: "AsposePdfRepair"
second_title: "Aspose.PDF för Node.js via C++"
description: "Reparera en PDF-fil."
type: docs
url: /sv/nodejs-cpp/organize/asposepdfrepair/
---

_Reparera en PDF-fil._

```js
function AsposePdfRepair(
    fileName,
    fileNameResult
)
```

**Parameters**: 

* **fileName** file name 
* **fileNameResult** result file name 

**Return**: 
JSON-objekt
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Repair a PDF-file and save the "ResultPdfRepair.pdf"*/
    const json = AsposePdfModule.AsposePdfRepair(pdf_file, "ResultPdfRepair.pdf");
    console.log("AsposePdfRepair => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Repair a PDF-file and save the "ResultPdfRepair.pdf"*/
const json = AsposePdfModule.AsposePdfRepair(pdf_file, "ResultPdfRepair.pdf");
console.log("AsposePdfRepair => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```