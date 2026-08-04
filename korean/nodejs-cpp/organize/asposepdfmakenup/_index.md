---
title: "AsposePdfMakeNUp"
second_title: "C++를 통해 Node.js용 Aspose.PDF"
description: "PDF 파일에서 N-Up 문서를 만듭니다."
type: docs
url: /ko/nodejs-cpp/organize/asposepdfmakenup/
---

_PDF 파일에서 N-Up 문서를 만듭니다._

```js
function AsposePdfMakeNUp(
    fileName,
    columns,
    rows,
    fileNameResult 
)
```

**Parameters**: 

* **fileName** file name 
* **columns** count of columns
* **rows** count of rows
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
    const columns = 2
    const rows = 2
    /*Make N-Up document from a PDF-file and save the "ResultMakeNUp.pdf"*/
    const json = AsposePdfModule.AsposePdfMakeNUp(pdf_file, columns, rows, "ResultMakeNUp.pdf");
    console.log("AsposePdfMakeNUp => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
const columns = 2
const rows = 2
/*Make N-Up document from a PDF-file and save the "ResultMakeNUp.pdf"*/
const json = AsposePdfModule.AsposePdfMakeNUp(pdf_file, columns, rows, "ResultMakeNUp.pdf");
console.log("AsposePdfMakeNUp => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```