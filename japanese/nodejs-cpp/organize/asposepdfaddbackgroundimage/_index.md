---
title: "AsposePdfAddBackgroundImage"
second_title: "C++ 経由で Node.js 用 Aspose.PDF"
description: "PDF ファイルに背景画像を追加します。"
type: docs
url: /ja/nodejs-cpp/organize/asposepdfaddbackgroundimage/
---

_PDFファイルに背景画像を追加します。_

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

JSON オブジェクト

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