---
title: "AsposePdfReplaceText"
second_title: "Aspose.PDF 用于 Node.js via C++"
description: "替换 PDF 文件中的文本。"
type: docs
url: /zh/nodejs-cpp/organize/asposepdfreplacetext/
---

_在 PDF 文件中替换文本。_

```js
function AsposePdfReplaceText(
    fileName,
    findText,
    replaceText,
    fileNameResult
)
```

**Parameters**: 

* **fileName** file name 
* **findText** text fragment to search
* **replaceText** text fragment to replace
* **fileNameResult** result file name 

**Return**: 

JSON 对象

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
    /*Replace text in a PDF-file and save the "ResultPdfReplaceText.pdf"*/
    const json = AsposePdfModule.AsposePdfReplaceText(pdf_file, findText, replaceText, "ResultPdfReplaceText.pdf");
    console.log("AsposePdfReplaceText => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
const findText = 'Aspose';
const replaceText = 'ASPOSE';
/*Replace text in a PDF-file and save the "ResultPdfReplaceText.pdf"*/
const json = AsposePdfModule.AsposePdfReplaceText(pdf_file, findText, replaceText, "ResultPdfReplaceText.pdf");
console.log("AsposePdfReplaceText => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```