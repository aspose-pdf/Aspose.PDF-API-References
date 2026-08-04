---
title: "AsposePdfDeleteWatermarks"
second_title: "Aspose.PDF per Node.js via C++"
description: "Elimina filigrane da un file PDF."
type: docs
url: /it/nodejs-cpp/organize/asposepdfdeletewatermarks/
---

_Elimina le filigrane da un file PDF._

```js
function AsposePdfDeleteWatermarks(
    fileName,
    fileNameResult
)
```

**Parameters**: 

* **fileName** file name 
* **fileNameResult** result file name 

**Return**: 
Oggetto JSON
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Delete watermarks from a PDF-file and save the "ResultPdfDeleteWatermarks.pdf"*/
    const json = AsposePdfModule.AsposePdfDeleteWatermarks(pdf_file, "ResultPdfDeleteWatermarks.pdf");
    console.log("AsposePdfDeleteWatermarks => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Delete watermarks from a PDF-file and save the "ResultPdfDeleteWatermarks.pdf"*/
const json = AsposePdfModule.AsposePdfDeleteWatermarks(pdf_file, "ResultPdfDeleteWatermarks.pdf");
console.log("AsposePdfDeleteWatermarks => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```