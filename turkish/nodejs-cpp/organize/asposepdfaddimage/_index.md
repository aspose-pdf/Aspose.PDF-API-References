---
title: "AsposePdfAddImage"
second_title: "Aspose.PDF için Node.js üzerinden C++."
description: "PDF-file'ın sonuna bir resim ekle."
type: docs
url: /tr/nodejs-cpp/organize/asposepdfaddimage/
---

_PDF dosyasının sonuna bir resim ekle._

```js
function AsposePdfAddImage(
    fileName,
    fileImage,
    fileNameResult 
)
```

**Parameters**: 

* **fileName** file name 
* **fileImage** image file name 
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
const image_file = 'Aspose.jpg';
AsposePdf().then(AsposePdfModule => {
    /*Add an image to end a PDF-file and save the "ResultImage.pdf"*/
    const json = AsposePdfModule.AsposePdfAddImage(pdf_file, image_file, "ResultAddImage.pdf");
    console.log("AsposePdfAddImage => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
const image_file = 'Aspose.jpg';
/*Add an image to end a PDF-file and save the "ResultImage.pdf"*/
const json = AsposePdfModule.AsposePdfAddImage(pdf_file, image_file, "ResultAddImage.pdf");
console.log("AsposePdfAddImage => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```