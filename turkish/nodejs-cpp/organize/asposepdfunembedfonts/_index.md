---
title: "AsposePdfUnembedFonts"
second_title: "Aspose.PDF için Node.js üzerinden C++."
description: "PDF-file'dan yazı tiplerini gömme."
type: docs
url: /tr/nodejs-cpp/organize/asposepdfunembedfonts/
---

_PDF dosyasındaki gömülü fontları kaldır._

```js
function AsposePdfUnembedFonts(
    fileName,
    fileNameResult 
)
```

**Parameters**: 

* **fileName** file name 
* **fileNameResult** result file name 

**Return**: 
JSON nesnesi
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Unembed fonts a PDF-file and save the "ResultUnembedFonts.pdf"*/
    const json = AsposePdfModule.AsposePdfUnembedFonts(pdf_file, "ResultUnembedFonts.pdf");
    console.log("AsposePdfUnembedFonts => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Unembed fonts a PDF-file and save the "ResultUnembedFonts.pdf"*/
const json = AsposePdfModule.AsposePdfUnembedFonts(pdf_file, "ResultUnembedFonts.pdf");
console.log("AsposePdfUnembedFonts => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```