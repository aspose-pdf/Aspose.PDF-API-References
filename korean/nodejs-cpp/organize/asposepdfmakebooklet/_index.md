---
title: "AsposePdfMakeBooklet"
second_title: "C++를 통해 Node.js용 Aspose.PDF"
description: "PDF 파일에서 소책자를 만듭니다."
type: docs
url: /ko/nodejs-cpp/organize/asposepdfmakebooklet/
---

_PDF 파일로 소책자를 만듭니다._

```js
function AsposePdfMakeBooklet(
    fileName,
    fileNameResult 
)
```

**Parameters**: 

* **fileName** file name 
* **fileNameResult** result file name 

**Return**: 
JSON 객체
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Make booklet from a PDF-file and save the "ResultMakeBooklet.pdf"*/
    const json = AsposePdfModule.AsposePdfMakeBooklet(pdf_file, "ResultMakeBooklet.pdf");
    console.log("AsposePdfMakeBooklet => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Make booklet from a PDF-file and save the "ResultMakeBooklet.pdf"*/
const json = AsposePdfModule.AsposePdfMakeBooklet(pdf_file, "ResultMakeBooklet.pdf");
console.log("AsposePdfMakeBooklet => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```