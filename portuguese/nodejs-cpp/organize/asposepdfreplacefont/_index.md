---
title: "AsposePdfReplaceFont"
second_title: "Aspose.PDF para Node.js via C++"
description: "Substituir fonte em um arquivo PDF."
type: docs
url: /pt/nodejs-cpp/organize/asposepdfreplacefont/
---

_Substituir fonte em um arquivo PDF._

```js
function AsposePdfReplaceFont(
    fileName,
    findFont,
    replaceFont,
    fileNameResult
)
```

**Parameters**: 

* **fileName** file name 
* **findFont** name font to be replaced
* **replaceFont** replacement font name
* **fileNameResult** result file name 

**Return**: 

Objeto JSON

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    const findFont = 'Helvetica';
    const replaceFont = 'Times';
    /*Replace font Helvetica to Times in a PDF-file and save the "ResultPdfReplaceFont.pdf"*/
    const json = AsposePdfModule.AsposePdfReplaceFont(pdf_file, findFont, replaceFont, "ResultPdfReplaceFont.pdf");
    console.log("AsposePdfReplaceFont => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
const findFont = 'Helvetica';
const replaceFont = 'Times';
/*Replace font Helvetica to Times in a PDF-file and save the "ResultPdfReplaceFont.pdf"*/
const json = AsposePdfModule.AsposePdfReplaceFont(pdf_file, findFont, replaceFont, "ResultPdfReplaceFont.pdf");
console.log("AsposePdfReplaceFont => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```