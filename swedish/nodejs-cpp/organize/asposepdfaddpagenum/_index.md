---
title: "AsposePdfAddPageNum"
second_title: "Aspose.PDF för Node.js via C++"
description: "Lägg till sidnummer i en PDF-fil."
type: docs
url: /sv/nodejs-cpp/organize/asposepdfaddpagenum/
---

_Lägg till sidnummer i en PDF-fil._

```js
function AsposePdfAddPageNum(
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
    /*Add page number to a PDF-file save the "ResultAddPageNum.pdf"*/
    const json = AsposePdfModule.AsposePdfAddPageNum(pdf_file, "ResultAddPageNum.pdf");
    console.log("AsposePdfAddPageNum => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Add page number to a PDF-file and save the "ResultAddPageNum.pdf"*/
const json = AsposePdfModule.AsposePdfAddPageNum(pdf_file, "ResultAddPageNum.pdf");
console.log("AsposePdfAddPageNum => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```