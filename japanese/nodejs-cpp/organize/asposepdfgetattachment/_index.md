---
title: "AsposePdfGetAttachment"
second_title: "C++ 経由で Node.js 用 Aspose.PDF"
description: "PDF ファイルから添付ファイルを取得する。"
type: docs
url: /ja/nodejs-cpp/organize/asposepdfgetattachment/
---

_PDFファイルから添付ファイルを取得します。_

```js
function AsposePdfGetAttachment(
    fileName,
    fileNameResult
)
```

**Parameters**: 
  * **fileName** file name 
  * **fileNameResult** result file name template (for sample: "ResultPdfGetAttachment_{0}" where {0} - name of attachment) 

**Return**: 
JSON オブジェクト
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **filesCount** - attachment files count
  * **filesNameResult** - array of result filenames


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Get attachment from a PDF-file and save with template "ResultPdfGetAttachment_{0}" ({0} - name of attachment)*/
    const json = AsposePdfModule.AsposePdfGetAttachment(pdf_file, "ResultPdfGetAttachment_{0}");
    console.log("AsposePdfGetAttachment => %O", json.errorCode == 0 ? json.filesNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Get attachment from a PDF-file and save with template "ResultPdfGetAttachment_{0}" ({0} - name of attachment)*/
const json = AsposePdfModule.AsposePdfGetAttachment(pdf_file, "ResultPdfGetAttachment_{0}");
console.log("AsposePdfGetAttachment => %O", json.errorCode == 0 ? json.filesNameResult : json.errorText);
```