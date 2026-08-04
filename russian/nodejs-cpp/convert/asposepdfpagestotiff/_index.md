---
title: "AsposePdfPagesToTiff"
second_title: "Aspose.PDF for Node.js via C++"
description: "Конвертировать PDF-файл в TIFF."
type: docs
url: /ru/nodejs-cpp/convert/asposepdfpagestotiff/
---

_Преобразовать PDF‑файл в TIFF._

```
function AsposePdfPagesToTiff(
    fileName,
    fileNameResult,
    resolution
)
```

**Parameters**: 
  * **fileName** file name 
  * **fileNameResult** result file name template (for sample: "ResultPdfToTiff{0:D2}.tiff" where {0}, {0:D2}, {0:D3}, {0:Dn} - format page number) 
  * **resolution** image resolution, default 300 dpi

**Return**: 
Объект JSON
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **filesCount** - tiff files count
  * **filesNameResult** - array of result filenames


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Convert a PDF-file to TIFF with template "ResultPdfToTiff{0:D2}.tiff" ({0}, {0:D2}, {0:D3}, ... format page number), resolution 150 DPI and save*/
    const json = AsposePdfModule.AsposePdfPagesToTiff(pdf_file, "ResultPdfToTiff{0:D2}.tiff", 150);
    console.log("AsposePdfPagesToTiff => %O", json.errorCode == 0 ? json.filesNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Convert a PDF-file to TIFF with template "ResultPdfToTiff{0:D2}.tiff" ({0}, {0:D2}, {0:D3}, ... format page number), resolution 150 DPI and save*/
const json = AsposePdfModule.AsposePdfPagesToTiff(pdf_file, "ResultPdfToTiff{0:D2}.tiff", 150);
console.log("AsposePdfPagesToTiff => %O", json.errorCode == 0 ? json.filesNameResult : json.errorText);
```