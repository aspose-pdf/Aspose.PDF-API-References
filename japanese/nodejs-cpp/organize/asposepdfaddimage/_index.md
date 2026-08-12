---
title: "AsposePdfAddImage"
second_title: "C++ 経由で Node.js 用 Aspose.PDF"
description: "PDF ファイルの末尾に画像を追加します。"
type: docs
url: /ja/nodejs-cpp/organize/asposepdfaddimage/
---

_PDFファイルの末尾に画像を追加します。_

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
JSON オブジェクト
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