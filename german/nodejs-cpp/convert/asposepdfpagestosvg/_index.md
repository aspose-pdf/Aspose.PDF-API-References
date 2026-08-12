---
title: "AsposePdfPagesToSvg"
second_title: "Aspose.PDF für Node.js via C++"
description: "Konvertiere eine PDF-Datei in SVG."
type: docs
url: /de/nodejs-cpp/convert/asposepdfpagestosvg/
---

_Konvertieren einer PDF-Datei zu SVG._

```
function AsposePdfPagesToSvg(
    fileName,
    fileNameResult
)
```

**Parameters**: 
  * **fileName** file name 
  * **fileNameResult** result file name

**Return**: 
JSON-Objekt
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **filesCount** - png files count
  * **filesNameResult** - array of result filenames


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Convert a PDF-file to SVG and save the "ResultPdfToSvg.svg"*/
    const json = AsposePdfModule.AsposePdfPagesToSvg(pdf_file, "ResultPdfToSvg.svg");
    console.log("AsposePdfPagesToSvg => %O", json.errorCode == 0 ? json.filesNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Convert a PDF-file to SVG and save the "ResultPdfToSvg.svg"*/
const json = AsposePdfModule.AsposePdfPagesToSvg(pdf_file, "ResultPdfToSvg.svg");
console.log("AsposePdfPagesToSvg => %O", json.errorCode == 0 ? json.filesNameResult : json.errorText);
```