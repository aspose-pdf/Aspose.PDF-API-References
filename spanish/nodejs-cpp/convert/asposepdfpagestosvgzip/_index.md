---
title: "AsposePdfPagesToSvgZip"
second_title: "Aspose.PDF para Node.js via C++"
description: "Convertir un archivo PDF a SVG(zip)."
type: docs
url: /es/nodejs-cpp/convert/asposepdfpagestosvgzip/
---

_Convertir un archivo PDF a SVG(zip)._

```
function AsposePdfPagesToSvgZip(
    fileName,
    fileNameResult
)
```

**Parameters**: 
  * **fileName** file name 
  * **fileNameResult** result file name

**Return**: 
Objeto JSON
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **filesNameResult** - array of result filenames


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Convert a PDF-file to SVG(zip) and save the "ResultPdfToSvgZip.zip"*/
    const json = AsposePdfModule.AsposePdfPagesToSvgZip(pdf_file, "ResultPdfToSvgZip.zip");
    console.log("AsposePdfPagesToSvgZip => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*convert a PDF-file to SVG zip and save the "ResultPdfToSvgZip.zip"*/
const json = AsposePdfModule.AsposePdfPagesToSvgZip(pdf_file, "ResultPdfToSvgZip.zip");
console.log("AsposePdfPagesToSvgZip => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText)
```