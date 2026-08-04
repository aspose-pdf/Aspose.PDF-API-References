---
title: "AsposePdfOptimize"
second_title: "Aspose.PDF för Node.js via C++"
description: "Optimera en PDF-fil."
type: docs
url: /sv/nodejs-cpp/organize/asposepdfoptimize/
---

_Optimera en PDF-fil._

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
JSON-objekt
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