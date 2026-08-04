---
title: "AsposePdfToDocXEnhanced"
second_title: "C++ 経由で Node.js 用 Aspose.PDF"
description: "PDF ファイルを拡張認識モードで DocX に変換します。"
type: docs
url: /ja/nodejs-cpp/convert/asposepdftodocxenhanced/
---

_PDF ファイルを拡張認識モード（完全に編集可能な表と段落）で DocX に変換します。_

```js
function AsposePdfToDocXEnhanced(
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
    /*Convert a PDF-file to DocX with Enhanced Recognition Mode (fully editable tables and paragraphs) and save the "ResultPDFtoDocXEnhanced.docx"*/
    const json = AsposePdfModule.AsposePdfToDocXEnhanced(pdf_file, "ResultPDFtoDocXEnhanced.docx");
    console.log("AsposePdfToDocXEnhanced => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Convert a PDF-file to DocX with Enhanced Recognition Mode (fully editable tables and paragraphs) and save the "ResultPDFtoDocXEnhanced.docx"*/
const json = AsposePdfModule.AsposePdfToDocXEnhanced(pdf_file, "ResultPDFtoDocXEnhanced.docx");
console.log("AsposePdfToDocXEnhanced => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```