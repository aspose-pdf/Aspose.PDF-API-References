---
title: "AsposePdfDeleteAnnotations"
second_title: "Aspose.PDF لـ Node.js عبر C++"
description: "حذف التعليقات التوضيحية من ملف PDF."
type: docs
url: /ar/nodejs-cpp/organize/asposepdfdeleteannotations/
---

_حذف التعليقات التوضيحية من PDF-file._

```js
function AsposePdfDeleteAnnotations(
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
    /*Delete annotations from a PDF-file and save the "ResultPdfDeleteAnnotations.pdf"*/
    const json = AsposePdfModule.AsposePdfDeleteAnnotations(pdf_file, "ResultPdfDeleteAnnotations.pdf");
    console.log("AsposePdfDeleteAnnotations => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Delete annotations from a PDF-file and save the "ResultPdfDeleteAnnotations.pdf"*/
const json = AsposePdfModule.AsposePdfDeleteAnnotations(pdf_file, "ResultPdfDeleteAnnotations.pdf");
console.log("AsposePdfDeleteAnnotations => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```