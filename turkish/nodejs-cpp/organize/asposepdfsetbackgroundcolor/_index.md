---
title: "AsposePdfSetBackgroundColor"
second_title: "Aspose.PDF için Node.js üzerinden C++."
description: "PDF-file için arka plan rengini ayarla."
type: docs
url: /tr/nodejs-cpp/organize/asposepdfsetbackgroundcolor/
---

_PDF-dosyası için arka plan rengini ayarla._

```js
function AsposePdfSetBackgroundColor(
    fileName,
    backgroundColor,
    fileNameResult
)
```

**Parameters**: 

* **fileName** file name 
* **backgroundColor** PDF background color (hexadecimal format "#RRGGBB", where RR-red, GG-green and BB-blue hexadecimal integers)
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
    /*Set the background color for the PDF-file and save the "ResultPdfSetBackgroundColor.pdf"*/
    const json = AsposePdfModule.AsposePdfSetBackgroundColor(pdf_file, "#426bf4", "ResultPdfSetBackgroundColor.pdf");
    console.log("AsposePdfSetBackgroundColor => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Set the background color for the PDF-file and save the "ResultPdfSetBackgroundColor.pdf"*/
const json = AsposePdfModule.AsposePdfSetBackgroundColor(pdf_file, "#426bf4", "ResultPdfSetBackgroundColor.pdf");
console.log("AsposePdfSetBackgroundColor => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```