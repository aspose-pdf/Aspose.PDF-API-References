---
title: "AsposePdfPagesToPng"
second_title: "Aspose.PDF untuk Node.js via C++"
description: "Konversi file PDF ke PNG."
type: docs
url: /id/nodejs-cpp/convert/asposepdfpagestopng/
---

_Konversi file PDF ke PNG._

```
function AsposePdfPagesToPng(
    fileName,
    fileNameResult,
    resolution
)
```

**Parameters**: 
  * **fileName** file name 
  * **fileNameResult** result file name template (for sample: "ResultPdfToPng{0:D2}.png" where {0}, {0:D2}, {0:D3}, {0:Dn} - format page number) 
  * **resolution** image resolution, default 300 dpi

**Return**: 
Objek JSON
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **filesCount** - png files count
  * **filesNameResult** - array of result filenames


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Convert a PDF-file to PNG with template "ResultPdfToPng{0:D2}.png" ({0}, {0:D2}, {0:D3}, ... format page number), resolution 150 DPI and save*/
    const json = AsposePdfModule.AsposePdfPagesToPng(pdf_file, "ResultPdfToPng{0:D2}.png", 150);
    console.log("AsposePdfPagesToPng => %O", json.errorCode == 0 ? json.filesNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Convert a PDF-file to PNG with template "ResultPdfToPng{0:D2}.png" ({0}, {0:D2}, {0:D3}, ... format page number), resolution 150 DPI and save*/
const json = AsposePdfModule.AsposePdfPagesToPng(pdf_file, "ResultPdfToPng{0:D2}.png", 150);
console.log("AsposePdfPagesToPng => %O", json.errorCode == 0 ? json.filesNameResult : json.errorText);
```