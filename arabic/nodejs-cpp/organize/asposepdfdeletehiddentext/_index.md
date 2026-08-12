---
title: "AsposePdfDeleteHiddenText"
second_title: "Aspose.PDF لـ Node.js عبر C++"
description: "حذف النص المخفي من ملف PDF."
type: docs
url: /ar/nodejs-cpp/organize/asposepdfdeletehiddentext/
---

_حذف النص المخفي من ملف PDF._

```js
function AsposePdfDeleteHiddenText(
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
    /*Delete hidden text from a PDF-file and save the "ResultPdfDeleteHiddenText.pdf"*/
    const json = AsposePdfModule.AsposePdfDeleteHiddenText(pdf_file, "ResultPdfDeleteHiddenText.pdf");
    console.log("AsposePdfDeleteHiddenText => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Delete hidden text from a PDF-file and save the "ResultPdfDeleteHiddenText.pdf"*/
const json = AsposePdfModule.AsposePdfDeleteHiddenText(pdf_file, "ResultPdfDeleteHiddenText.pdf");
console.log("AsposePdfDeleteHiddenText => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```