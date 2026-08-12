---
title: "AsposePdfRecover"
second_title: "C++ 経由で Node.js 用 Aspose.PDF"
description: "PDFファイルの構造を復元し、無効なデータをトリムします。"
type: docs
url: /ja/nodejs-cpp/organize/asposepdfrecover/
---

_PDFファイルの構造を復元し、無効なデータをトリムします._

```js
function AsposePdfRecover(
    fileName,
    fileNameResult
)
```

**Parameters**: 

* **fileName** file name 
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
AsposePdf().then(AsposePdfModule => {
    /*Recover a PDF-file structure and trims invalid data and save the "ResultPdfRecover.pdf"*/
    const json = AsposePdfModule.AsposePdfRecover(pdf_file, "ResultPdfRecover.pdf");
    console.log("AsposePdfRecover => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Recover a PDF-file structure and trims invalid data and save the "ResultPdfRecover.pdf"*/
const json = AsposePdfModule.AsposePdfRecover(pdf_file, "ResultPdfRecover.pdf");
console.log("AsposePdfRecover => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```