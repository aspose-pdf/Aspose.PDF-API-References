---
title: "AsposePdfDeletePages"
second_title: Aspose.PDF for Node.js via C++
description: "Delete pages from a PDF-file."
type: docs
url: /nodejs-cpp/organize/asposepdfdeletepages/
---

_Delete pages from a PDF-file._

```js
function AsposePdfDeletePages(
    fileName,
    fileNameResult,
    numPages
)
```

**Parameters**: 

* **fileName** file name 
* **fileNameResult** result file name
* **numPages** page numbers:
  * string, include page numbers with intervals as "7, 20, 22, 30-32, 33, 36-40, 46"
  * array, array of page numbers, such as [1,3]
  * number, page number as 2

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
    /*string, include number pages with interval: "7, 20, 22, 30-32, 33, 36-40, 46"*/
    /*const numPages = "1-3";*/
    /*array, array of number pages*/
    /*const numPages = [1,3];*/
    /*number, number page*/
    const numPages = 1;
    /*Delete pages from a PDF-file and save the "ResultDeletePages.pdf"*/
    const json = AsposePdfModule.AsposePdfDeletePages(pdf_file, "ResultDeletePages.pdf", numPages);
    console.log("AsposePdfDeletePages => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*string, include number pages with interval: "7, 20, 22, 30-32, 33, 36-40, 46"*/
/*const numPages = "1-3";*/
/*array, array of number pages*/
/*const numPages = [1,3];*/
/*number, number page*/
const numPages = 1;
/*Delete pages from a PDF-file and save the "ResultDeletePages.pdf"*/
const json = AsposePdfModule.AsposePdfDeletePages(pdf_file, "ResultDeletePages.pdf", numPages);
console.log("AsposePdfDeletePages => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```