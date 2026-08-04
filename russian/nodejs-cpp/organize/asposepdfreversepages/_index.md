---
title: "AsposePdfReversePages"
second_title: "Aspose.PDF for Node.js via C++"
description: "Изменить порядок страниц PDF‑файла на обратный."
type: docs
url: /ru/nodejs-cpp/organize/asposepdfreversepages/
---

_Обратить порядок страниц PDF-file._

```js
function AsposePdfReversePages(
    fileName,
    fileNameResult
)
```

**Parameters**: 

* **fileName** file name 
* **fileNameResult** result file name 

**Return**: 
Объект JSON
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Reverse the page order of a PDF-file and save the "ResultPdfReversePages.pdf"*/
    const json = AsposePdfModule.AsposePdfReversePages(pdf_file, "ResultPdfReversePages.pdf");
    console.log("AsposePdfReversePages => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Reverse the page order of a PDF-file and save the "ResultPdfReversePages.pdf"*/
const json = AsposePdfModule.AsposePdfReversePages(pdf_file, "ResultPdfReversePages.pdf");
console.log("AsposePdfReversePages => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```