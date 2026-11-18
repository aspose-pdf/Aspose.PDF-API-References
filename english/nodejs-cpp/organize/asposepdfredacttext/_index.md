---
title: "AsposePdfRedactText"
second_title: Aspose.PDF for Node.js via C++
description:  "Permanently redact and black out sensitive text in a PDF-file."
type: docs
url: /nodejs-cpp/organize/asposepdfredacttext/
---

_Permanently redact and black out sensitive text in a PDF-file._

```js
function AsposePdfRedactText(
    fileName,
    searchPattern,
    fileNameResult
)
```

**Parameters**: 

* **fileName** file name 
* **searchPattern**  regular expression (regex, C#-like syntax) pattern used to search
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
    const searchPattern = "aspose|pdf";
    /*Permanently redact and black out sensitive text in a PDF-file and save the "ResultPdfRedactText.pdf"*/
    const json = AsposePdfModule.AsposePdfRedactText(pdf_file, searchPattern, "ResultPdfRedactText.pdf");
    console.log("AsposePdfRedactText => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
const searchPattern = "aspose|pdf";
/*Permanently redact and black out sensitive text in a PDF-file and save the "ResultPdfRedactText.pdf"*/
const json = AsposePdfModule.AsposePdfRedactText(pdf_file, searchPattern, "ResultPdfRedactText.pdf");
console.log("AsposePdfRedactText => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```