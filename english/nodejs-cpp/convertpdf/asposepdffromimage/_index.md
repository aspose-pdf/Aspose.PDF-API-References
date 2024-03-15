---
title: "AsposePdfFromImage"
second_title: Aspose.PDF for Node.js via C++
description:  "Convert a Image-file to PDF."
type: docs
url: /nodejs-cpp/convertpdf/asposepdffromimage/
---

_Convert a Image-file to PDF._

```js
function AsposePdfFromImage(
    fileName,
    pdfPageSize,
    margin,
    isLandscape,
    fileNameResult 
)
```

**Parameters**: 

* **fileName** image file name (support bmp, jpeg, png, tiff, gif formats)
* **pdfPageSize**  page size:
  * Module.PdfPageSize.A0
  * Module.PdfPageSize.A1
  * Module.PdfPageSize.A2
  * Module.PdfPageSize.A3
  * Module.PdfPageSize.A4
  * Module.PdfPageSize.A5
  * Module.PdfPageSize.A6
  * Module.PdfPageSize.B5
  * Module.PdfPageSize.PageLetter
  * Module.PdfPageSize.PageLegal
  * Module.PdfPageSize.PageLedger
  * Module.PdfPageSize.P11x17
  * Module.PdfPageSize.ImageSize
* **margin** page margin
* **isLandscape** page landscape mode (0 or 1)
* **fileNameResult** result file name

**Return**: 
JSON object 
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('.//AsposePDFforNode.cjs');
const aspose_file = 'Aspose.jpg';
AsposePdf().then(AsposePdfModule => {
    /*Convert a Image-file to PDF and save the "ResultPDFFromImage.pdf"*/
    const json = AsposePdfModule.AsposePdfFromImage(aspose_file, AsposePdfModule.PdfPageSize.A4, 10, false, "ResultPdfFromImage.pdf");
    console.log("AsposePdfFromImage => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from './/AsposePDFforNode.mjs';
const AsposePdfModule = await AsposePdf();
const aspose_file = 'Aspose.jpg';
/*Convert a Image-file to PDF and save the "ResultPDFFromImage.pdf"*/
const json = AsposePdfModule.AsposePdfFromImage(aspose_file, AsposePdfModule.PdfPageSize.A4, 10, false, "ResultPdfFromImage.pdf");
console.log("AsposePdfFromImage => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```