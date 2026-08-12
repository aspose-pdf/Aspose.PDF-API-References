---
title: "AsposePdfToXps"
second_title: "Aspose.PDF 用于 Node.js via C++"
description: "将 PDF 文件转换为 Xps。"
type: docs
url: /zh/nodejs-cpp/convert/asposepdftoxps/
---

_将 PDF 文件转换为 Xps。_

```js
function AsposePdfToXps(
    fileName,
    fileNameResult 
)
```

**Parameters**: 

* **fileName** file name 
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
AsposePdf().then(AsposePdfModule => {
    /*Convert a PDF-file to Xps and save the "ResultPDFtoXps.xps"*/
    const json = AsposePdfModule.AsposePdfToXps(pdf_file, "ResultPDFtoXps.xps");
    console.log("AsposePdfToXps => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Convert a PDF-file to Xps and save the "ResultPDFtoXps.xps"*/
const json = AsposePdfModule.AsposePdfToXps(pdf_file, "ResultPDFtoXps.xps");
console.log("AsposePdfToXps => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```