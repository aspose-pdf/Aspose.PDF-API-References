---
title: "AsposePdfDeleteBlankPages"
second_title: "Aspose.PDF for Node.js via C++"
description: "Удалить пустые страницы из PDF-файла."
type: docs
url: /ru/nodejs-cpp/organize/asposepdfdeleteblankpages/
---

_Удалить пустые страницы из PDF-file._

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
Объект JSON
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