---
title: "AsposePdfDeleteHiddenText"
second_title: Aspose.PDF for Node.js via C++
description:  "Delete hidden text from a PDF-file."
type: docs
url: /nodejs-cpp/organize/asposepdfdeletehiddentext/
---

_Delete hidden text from a PDF-file._

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
JSON object 
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