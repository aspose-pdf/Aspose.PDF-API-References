---
title: "AsposePdfDeleteBlankPages"
second_title: "Aspose.PDF untuk Node.js via C++"
description: "Hapus halaman kosong dari PDF-file."
type: docs
url: /id/nodejs-cpp/organize/asposepdfdeleteblankpages/
---

_Menghapus halaman kosong dari file PDF._

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
Objek JSON
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