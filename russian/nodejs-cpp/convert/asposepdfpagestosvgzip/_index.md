---
title: "AsposePdfPagesToSvgZip"
second_title: "Aspose.PDF for Node.js via C++"
description: "Конвертировать PDF-файл в SVG(zip)."
type: docs
url: /ru/nodejs-cpp/convert/asposepdfpagestosvgzip/
---

_Преобразовать PDF-файл в SVG(zip)._

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
Объект JSON
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