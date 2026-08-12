---
title: "AsposePdfDeleteTables"
second_title: "C++ 経由で Node.js 用 Aspose.PDF"
description: "PDF ファイルから表を削除する。"
type: docs
url: /ja/nodejs-cpp/organize/asposepdfdeletetables/
---

_PDFファイルからテーブルを削除します。_

```js
function AsposePdfDeleteTables(
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
    /*Delete tables from a PDF-file and save the "ResultPdfDeleteTables.pdf"*/
    const json = AsposePdfModule.AsposePdfDeleteTables(pdf_file, "ResultPdfDeleteTables.pdf");
    console.log("AsposePdfDeleteTables => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Delete tables from a PDF-file and save the "ResultPdfDeleteTables.pdf"*/
const json = AsposePdfModule.AsposePdfDeleteTables(pdf_file, "ResultPdfDeleteTables.pdf");
console.log("AsposePdfDeleteTables => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```