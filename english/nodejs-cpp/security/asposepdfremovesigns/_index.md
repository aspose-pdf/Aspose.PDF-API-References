---
title: "AsposePdfRemoveSigns"
second_title: Aspose.PDF for Node.js via C++
description:  "Remove all digital signatures from a PDF-file."
type: docs
url: /nodejs-cpp/security/asposepdfremovesigns/
---

_Remove all digital signatures from a PDF-file._

```js
function AsposePdfRemoveSigns(
    fileName,
    fileNameResult 
)
```

**Parameters**: 

* **fileName** file name 
* **password** user password 
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
    /*Remove all digital signatures from a PDF-file and save the "ResultRemoveSigns.pdf"*/
    const json = AsposePdfModule.AsposePdfRemoveSigns(pdf_file, "ResultRemoveSigns.pdf");
    console.log("AsposePdfRemoveSigns => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Remove all digital signatures from a PDF-file and save the "ResultRemoveSigns.pdf"*/
const json = AsposePdfModule.AsposePdfRemoveSigns(pdf_file, "ResultRemoveSigns.pdf");
console.log("AsposePdfRemoveSigns => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```