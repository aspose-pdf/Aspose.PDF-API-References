---
title: "AsposePdfAddImage"
second_title: "C++를 통해 Node.js용 Aspose.PDF"
description: "PDF 파일의 끝에 이미지를 추가합니다."
type: docs
url: /ko/nodejs-cpp/organize/asposepdfaddimage/
---

_PDF 파일 끝에 이미지를 추가합니다._

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
JSON 객체
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