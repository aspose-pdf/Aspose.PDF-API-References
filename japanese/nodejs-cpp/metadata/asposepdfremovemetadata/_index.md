---
title: "AsposePdfRemoveMetadata"
second_title: "C++ 経由で Node.js 用 Aspose.PDF"
description: "PDFファイルからメタデータを削除します。"
type: docs
url: /ja/nodejs-cpp/metadata/asposepdfremovemetadata/
---

_PDF ファイルからメタデータを削除します。_

```js
function AsposePdfRemoveMetadata(
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
    /*Remove metadata from a PDF-file and save the "ResultPdfRemoveMetadata.pdf"*/
    const json = AsposePdfModule.AsposePdfRemoveMetadata(pdf_file, "ResultPdfRemoveMetadata.pdf");
    console.log("AsposePdfRemoveMetadata => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Remove metadata from a PDF-file and save the "ResultPdfRemoveMetadata.pdf"*/
const json = AsposePdfModule.AsposePdfRemoveMetadata(pdf_file, "ResultPdfRemoveMetadata.pdf");
console.log("AsposePdfRemoveMetadata => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```