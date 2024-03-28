---
title: "AsposePdfFromTxt"
second_title: Aspose.PDF for Node.js via C++
description:  "Convert a TXT-file to PDF."
type: docs
url: /nodejs-cpp/convertpdf/asposepdffromtxt/
---

_Convert a TXT-file to PDF._

```js
function AsposePdfFromTxt(
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
const txt_file = 'ReadMe.txt';
AsposePdf().then(AsposePdfModule => {
    /*Convert a TXT-file to PDF and save the "ResultPDFFromTxt.pdf"*/
    const json = AsposePdfModule.AsposePdfFromTxt(txt_file, "ResultPDFFromTxt.pdf");
    console.log("AsposePdfFromTxt => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const txt_file = 'ReadMe.txt';
/*Convert a TXT-file to PDF and save the "ResultPDFFromTxt.pdf"*/
const json = AsposePdfModule.AsposePdfFromTxt(txt_file, "ResultPDFFromTxt.pdf");
console.log("AsposePdfFromTxt => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```