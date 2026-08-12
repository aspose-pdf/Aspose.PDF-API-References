---
title: "AsposePdfDeleteBlankPages"
second_title: "Aspose.PDF için Node.js üzerinden C++."
description: "PDF-file'dan boş sayfaları sil."
type: docs
url: /tr/nodejs-cpp/organize/asposepdfdeleteblankpages/
---

_PDF-dosyasından boş sayfaları sil._

```js
function AsposePdfDeleteBlankPages(
    fileName,
    fileNameResult 
)
```

**Parameters**: 

* **fileName** file name 
* **fileNameResult** result file name 

**Return**: 
JSON nesnesi
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Delete blank pages from a PDF-file and save the "ResultDeleteBlankPages.pdf"*/
    const json = AsposePdfModule.AsposePdfDeleteBlankPages(pdf_file, "ResultDeleteBlankPages.pdf");
    console.log("AsposePdfDeleteBlankPages => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Delete blank pages from a PDF-file and save the "ResultDeleteBlankPages.pdf"*/
const json = AsposePdfModule.AsposePdfDeleteBlankPages(pdf_file, "ResultDeleteBlankPages.pdf");
console.log("AsposePdfDeleteBlankPages => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```