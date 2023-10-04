---
title: "AsposePdfDeleteJavaScripts"
second_title: Aspose.PDF for Node.js via C++
description:  "Delete JavaScripts from a PDF-file."
type: docs
url: /nodejs-cpp/organize/asposepdfdeletejavascripts/
---

_Delete JavaScripts from a PDF-file._

```js
function AsposePdfDeleteJavaScripts(
    fileName,
    fileNameResult
)
```

**Parameters**: 

* **fileName** file name 
* **fileNameResult** result file name 

**Return**: 
JSON object 
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('.//AsposePDFforNode.cjs');
const pdf_file = 'ReadMe.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Delete JavaScripts from a PDF-file and save the "ResultPdfDeleteJavaScripts.pdf"*/
    const json = AsposePdfModule.AsposePdfDeleteJavaScripts(pdf_file, "ResultPdfDeleteJavaScripts.pdf");
    console.log("AsposePdfDeleteJavaScripts => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from './/AsposePDFforNode.mjs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'ReadMe.pdf';
/*Delete JavaScripts from a PDF-file and save the "ResultPdfDeleteJavaScripts.pdf"*/
const json = AsposePdfModule.AsposePdfDeleteJavaScripts(pdf_file, "ResultPdfDeleteJavaScripts.pdf");
console.log("AsposePdfDeleteJavaScripts => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```