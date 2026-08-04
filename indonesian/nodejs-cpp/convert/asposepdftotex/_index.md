---
title: "AsposePdfToTeX"
second_title: "Aspose.PDF untuk Node.js via C++"
description: "Konversi file PDF ke TeX."
type: docs
url: /id/nodejs-cpp/convert/asposepdftotex/
---

_Konversi file PDF ke TeX._

```js
function AsposePdfToTeX(
    fileName,
    fileNameResult 
)
```

**Parameters**: 

* **fileName** file name 
* **fileNameResult** result file name 

**Return**: 
Objek JSON
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Convert a PDF-file to TeX and save the "ResultPDFtoTeX.tex"*/
    const json = AsposePdfModule.AsposePdfToTeX(pdf_file, "ResultPDFtoTeX.tex");
    console.log("AsposePdfToTeX => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Convert a PDF-file to TeX and save the "ResultPDFtoTeX.tex"*/
const json = AsposePdfModule.AsposePdfToTeX(pdf_file, "ResultPDFtoTeX.tex");
console.log("AsposePdfToTeX => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```