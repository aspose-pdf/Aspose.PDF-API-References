---
title: "AsposePdfReorderPages"
second_title: Aspose.PDF for Node.js via C++
description: "Reorder pages in a PDF-file."
type: docs
url: /nodejs-cpp/organize/asposepdfreorderpages/
---

_Reorder pages in a PDF-file._

```js
function AsposePdfReorderPages(
    fileName,
    fileNameResult,
    numPages
)
```

**Parameters**: 

* **fileName** file name 
* **fileNameResult** result file name
* **numPages** array, source page numbers in the desired order, 1-based

**Return**: 

JSON object 

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*array, source page numbers in the desired order, 1-based*/
    const numPages = [2];
    /*Reorder pages in a PDF-file and save the "ResultReorderPages.pdf"*/
    const json = AsposePdfModule.AsposePdfReorderPages(pdf_file, "ResultReorderPages.pdf", numPages);
    console.log("AsposePdfReorderPages => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*array, source page numbers in the desired order, 1-based*/
const numPages = [3,2];
/*Reorder pages from a PDF-file and save the "ResultReorderPages.pdf"*/
const json = AsposePdfModule.AsposePdfReorderPages(pdf_file, "ResultReorderPages.pdf", numPages);
console.log("AsposePdfReorderPages => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```