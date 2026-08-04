---
title: "AsposePdfExportXfdf"
second_title: "C++ 経由で Node.js 用 Aspose.PDF"
description: "AcroForm を含む PDF ファイルを XFDF にエクスポートします。"
type: docs
url: /ja/nodejs-cpp/convert/asposepdfexportxfdf/
---

_AcroForm を使用した PDF ファイルから XFDF にエクスポートします._

```js
function AsposePdfExportXfdf(
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
    /*Export from a PDF-file with AcroForm to XFDF and save the "ResultPdfExportXfdf.xfdf"*/
    const json = AsposePdfModule.AsposePdfExportXfdf(pdf_file, "ResultPdfExportXfdf.xfdf");
    console.log("AsposePdfExportXfdf => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Export from a PDF-file with AcroForm to XFDF and save the "ResultPdfExportXfdf.xfdf"*/
const json = AsposePdfModule.AsposePdfExportXfdf(pdf_file, "ResultPdfExportXfdf.xfdf");
console.log("AsposePdfExportXfdf => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```