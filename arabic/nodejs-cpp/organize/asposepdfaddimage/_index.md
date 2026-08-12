---
title: "AsposePdfAddImage"
second_title: "Aspose.PDF لـ Node.js عبر C++"
description: "إضافة صورة إلى نهاية ملف PDF."
type: docs
url: /ar/nodejs-cpp/organize/asposepdfaddimage/
---

_أضف صورة إلى نهاية ملف PDF._

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
كائن JSON
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