---
title: "AsposePdfOptimize"
second_title: Aspose.PDF for Node.js via C++
description:  "Optimize a PDF-file."
type: docs
url: /nodejs-cpp/organize/asposepdfoptimize/
---

_Optimize a PDF-file._

```js
function AsposePdfOptimize(
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
    /*Optimize a PDF-file and save the "ResultOptimize.pdf"*/
    const json = AsposePdfModule.AsposePdfOptimize(pdf_file, "ResultOptimize.pdf");
    console.log("AsposePdfOptimize => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Optimize a PDF-file and save the "ResultOptimize.pdf"*/
const json = AsposePdfModule.AsposePdfOptimize(pdf_file, "ResultOptimize.pdf");
console.log("AsposePdfOptimize => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```