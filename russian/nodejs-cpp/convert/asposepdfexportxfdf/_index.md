---
title: "AsposePdfExportXfdf"
second_title: "Aspose.PDF for Node.js via C++"
description: "Экспорт из PDF‑файла с AcroForm в XFDF."
type: docs
url: /ru/nodejs-cpp/convert/asposepdfexportxfdf/
---

_Экспортировать из PDF-файла с AcroForm в XFDF._

```js
function AsposePdfExportXfdf(
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
  * **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Export from a PDF-file with AcroForm to XFDF and save the "ResultPdfExportXfdf.xfdf"*/
    const json = AsposePdfModule.AsposePdfExportXfdf(pdf_file, "ResultPdfExportXfdf.xfdf");
    console.log("AsposePdfExportXfdf => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Export from a PDF-file with AcroForm to XFDF and save the "ResultPdfExportXfdf.xfdf"*/
const json = AsposePdfModule.AsposePdfExportXfdf(pdf_file, "ResultPdfExportXfdf.xfdf");
console.log("AsposePdfExportXfdf => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```