---
title: "AsposePdfFlatten"
second_title: Aspose.PDF for Node.js via C++
description:  "Flatten a PDF-file."
type: docs
url: /nodejs-cpp/organize/asposepdfflatten/
---

_Flatten a PDF-file._

```js
function AsposePdfFlatten(
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
    /*Flatten a PDF-file and save the "ResultFlatten.pdf"*/
    const json = AsposePdfModule.AsposePdfFlatten(pdf_file, "ResultFlatten.pdf");
    console.log("AsposePdfFlatten => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Flatten a PDF-file and save the "ResultFlatten.pdf"*/
const json = AsposePdfModule.AsposePdfFlatten(pdf_file, "ResultFlatten.pdf");
console.log("AsposePdfFlatten => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```