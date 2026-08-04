---
title: "AsposePdfOptimizeFileSize"
second_title: "Aspose.PDF untuk Node.js via C++"
description: "Optimalkan ukuran PDF-file dengan kualitas kompresi gambar."
type: docs
url: /id/nodejs-cpp/organize/asposepdfoptimizefilesize/
---

_Optimalkan ukuran PDF-file dengan kualitas kompresi gambar._

```js
function AsposePdfOptimizeFileSize(
    fileName,
    imageQuality,
    fileNameResult 
)
```

**Parameters**: 

* **fileName** file name 
* **imageQuality** image compression quality
* **fileNameResult** result file name 

**Return**: 
Objek JSON
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    const imageQuality = 50;
    /*Optimize size of PDF-file with image compression quality and save the "ResultPdfOptimizeFileSize.pdf"*/
    const json = AsposePdfModule.AsposePdfOptimizeFileSize(pdf_file, imageQuality, "ResultPdfOptimizeFileSize.pdf");
    console.log("AsposePdfOptimizeFileSize => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
const imageQuality = 50;
/*Optimize size of PDF-file with image compression quality and save the "ResultPdfOptimizeFileSize.pdf"*/
const json = AsposePdfModule.AsposePdfOptimizeFileSize(pdf_file, imageQuality, "ResultPdfOptimizeFileSize.pdf");
console.log("AsposePdfOptimizeFileSize => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```