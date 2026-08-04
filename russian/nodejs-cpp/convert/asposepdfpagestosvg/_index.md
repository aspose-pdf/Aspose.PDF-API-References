---
title: "AsposePdfPagesToSvg"
second_title: "Aspose.PDF for Node.js via C++"
description: "Конвертировать PDF-файл в SVG."
type: docs
url: /ru/nodejs-cpp/convert/asposepdfpagestosvg/
---

_Преобразовать PDF-файл в SVG._

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
Объект JSON
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