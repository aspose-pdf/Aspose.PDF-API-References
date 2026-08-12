---
title: "AsposePdfToMarkdown"
second_title: "Aspose.PDF untuk Node.js via C++"
description: "Konversi file PDF ke Markdown."
type: docs
url: /id/nodejs-cpp/convert/asposepdftomarkdown/
---

_Konversi file PDF ke Markdown._

```js
function AsposePdfToMarkdown(
    fileName,
    fileNameResult 
)
```

**Parameters**: 

* **fileName** file name 
* **fileNameResult** result file name 

**Return**: 
Objek JSON
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Convert a PDF-file to Markdown and save the "ResultPDFtoMarkdown.md"*/
    const json = AsposePdfModule.AsposePdfToMarkdown(pdf_file, "ResultPDFtoMarkdown.md");
    console.log("AsposePdfToMarkdown => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Convert a PDF-file to Markdown and save the "ResultPDFtoMarkdown.md"*/
const json = AsposePdfModule.AsposePdfToMarkdown(pdf_file, "ResultPDFtoMarkdown.md");
console.log("AsposePdfToMarkdown => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```