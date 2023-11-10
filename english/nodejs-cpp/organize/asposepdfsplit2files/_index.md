---
title: "AsposePdfSplit2Files"
second_title: Aspose.PDF for Node.js via C++
description:  "Split to two PDF-files."
type: docs
url: /nodejs-cpp/organize/asposepdfsplit2files/
---

_Split to two PDF-files._

```js
function AsposePdfSplit2Files(
    fileName,
    pageToSplit,
    fileNameResult1,
    fileNameResult2 
)
```

**Parameters**: 

* **fileName** file name 
* **pageToSplit** number page for split 
* **fileNameResult1** result file name #1 
* **fileNameResult2** result file name #2 

**Return**:

JSON object

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **fileNameResult1** - result file name #1
* **fileNameResult2** - result file name #2


**CommonJS**:

```js
const AsposePdf = require('.//AsposePDFforNode.cjs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Set number a page to split*/
    const pageToSplit = 1;
    /*Split to two PDF-files and save the "ResultSplit1.pdf", "ResultSplit2.pdf"*/
    const json = AsposePdfModule.AsposePdfSplit2Files(pdf_file, pageToSplit, "ResultSplit1.pdf", "ResultSplit2.pdf");
    console.log("AsposePdfSplit2Files => %O", json.errorCode == 0 ? [json.fileNameResult1, json.fileNameResult2] : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from './/AsposePDFforNode.mjs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Set number a page to split*/
const pageToSplit = 1;
/*Split to two PDF-files and save the "ResultSplit1.pdf", "ResultSplit2.pdf"*/
const json = AsposePdfModule.AsposePdfSplit2Files(pdf_file, pageToSplit, "ResultSplit1.pdf", "ResultSplit2.pdf");
console.log("AsposePdfSplit2Files => %O", json.errorCode == 0 ? [json.fileNameResult1, json.fileNameResult2] : json.errorText);
```