---
title: "AsposePdfToTxt"
second_title: "Aspose.PDF لـ Node.js عبر C++"
description: "تحويل ملف PDF إلى Txt."
type: docs
url: /ar/nodejs-cpp/convert/asposepdftotxt/
---

_تحويل ملف PDF إلى Txt._

```js
function AsposePdfToTxt(
    fileName,
    fileNameResult 
)
```

**Parameters**: 

* **fileName** file name 
* **fileNameResult** result file name 

**Return**: 
كائن JSON
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Convert a PDF-file to Txt and save the "ResultPDFtoTxt.txt"*/
    const json = AsposePdfModule.AsposePdfToTxt(pdf_file, "ResultPDFtoTxt.txt");
    console.log("AsposePdfToTxt => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Convert a PDF-file to Txt and save the "ResultPDFtoTxt.txt"*/
const json = AsposePdfModule.AsposePdfToTxt(pdf_file, "ResultPDFtoTxt.txt");
console.log("AsposePdfToTxt => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```