---
title: "AsposePdfDeleteJavaScripts"
second_title: "Aspose.PDF for Node.js via C++"
description: "Удалить JavaScript из PDF-файла."
type: docs
url: /ru/nodejs-cpp/organize/asposepdfdeletejavascripts/
---

_Удалить JavaScript из PDF‑файла._

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
Объект JSON
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Delete JavaScripts from a PDF-file and save the "ResultPdfDeleteJavaScripts.pdf"*/
    const json = AsposePdfModule.AsposePdfDeleteJavaScripts(pdf_file, "ResultPdfDeleteJavaScripts.pdf");
    console.log("AsposePdfDeleteJavaScripts => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Delete JavaScripts from a PDF-file and save the "ResultPdfDeleteJavaScripts.pdf"*/
const json = AsposePdfModule.AsposePdfDeleteJavaScripts(pdf_file, "ResultPdfDeleteJavaScripts.pdf");
console.log("AsposePdfDeleteJavaScripts => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```