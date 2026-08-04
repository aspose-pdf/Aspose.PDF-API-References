---
title: "AsposePdfAddBackgroundImage"
second_title: "Aspose.PDF 用于 Node.js via C++"
description: "向 PDF 文件添加背景图像。"
type: docs
url: /zh/nodejs-cpp/organize/asposepdfaddbackgroundimage/
---

_向 PDF 文件添加背景图像。_

```js
function AsposePdfAddBackgroundImage(
    fileName,
    fileBackgroundImage,
    fileNameResult
)
```

**Parameters**: 

* **fileName** file name 
* **fileBackgroundImage** image file name 
* **fileNameResult** result file name 

**Return**: 

JSON 对象

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
const background_file = 'Aspose.jpg';
AsposePdf().then(AsposePdfModule => {
    /*Add background image to a PDF-file and save the "ResultBackgroundImage.pdf"*/
    const json = AsposePdfModule.AsposePdfAddBackgroundImage(pdf_file, background_file, "ResultAddBackgroundImage.pdf");
    console.log("AsposePdfAddBackgroundImage => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
const background_file = 'Aspose.jpg';
/*Add background image to a PDF-file and save the "ResultBackgroundImage.pdf"*/
const json = AsposePdfModule.AsposePdfAddBackgroundImage(pdf_file, background_file, "ResultAddBackgroundImage.pdf");
console.log("AsposePdfAddBackgroundImage => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```