---
title: "AsposePdfReplaceTextPages"
second_title: Aspose.PDF for Node.js via C++
description: "Replace text on pages in a PDF-file."
type: docs
url: /nodejs-cpp/organize/asposepdfreplacetextpages/
---

_Replace text on pages in a PDF-file._

```js
function AsposePdfReplaceTextPages(
    fileName,
    findText,
    replaceText,
    numPages,
    fileNameResult
)
```

**Parameters**: 

* **fileName** file name 
* **findText** text fragment to search
* **replaceText** text fragment to replace
* **numPages** page numbers:
  * string, include page numbers with intervals as "7, 20, 22, 30-32, 33, 36-40, 46"
  * array, array of page numbers, such as [1,3]
  * number, page number as 2
* **fileNameResult** result file name

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
    const findText = 'Aspose';
    const replaceText = 'ASPOSE';

    /*string, include number pages with interval: "7, 20, 22, 30-32, 33, 36-40, 46"*/
    /*const numPages = "1-3";*/
    /*array, array of number pages*/
    /*const numPages = [1,3];*/
    /*number, number page*/
    const numPages = 1;

    /*Replace text on first page in a PDF-file and save the "ResultPdfReplaceTextPages.pdf"*/
    const json = AsposePdfModule.AsposePdfReplaceTextPages(pdf_file, findText, replaceText, numPages, "ResultPdfReplaceTextPages.pdf");
    console.log("AsposePdfReplaceTextPages => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
const findText = 'Aspose';
const replaceText = 'ASPOSE';

/*string, include number pages with interval: "7, 20, 22, 30-32, 33, 36-40, 46"*/
/*const numPages = "1-3";*/
/*array, array of number pages*/
/*const numPages = [1,3];*/
/*number, number page*/
const numPages = 1;

/*Replace text on first page in a PDF-file and save the "ResultPdfReplaceTextPages.pdf"*/
const json = AsposePdfModule.AsposePdfReplaceTextPages(pdf_file, findText, replaceText, numPages, "ResultPdfReplaceTextPages.pdf");
console.log("AsposePdfReplaceTextPages => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```