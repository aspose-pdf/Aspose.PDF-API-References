---
title: "AsposePdfAddAttachment"
second_title: "C++를 통해 Node.js용 Aspose.PDF"
description: "PDF 파일에 첨부 파일을 추가합니다."
type: docs
url: /ko/nodejs-cpp/organize/asposepdfaddattachment/
---

_PDF 파일에 첨부 파일을 추가합니다._

```js
function AsposePdfAddAttachment(
    fileName,
    fileAttachment,
    fileDescription,
    fileNameResult 
)
```

**Parameters**: 

* **fileName** file name
* **fileAttachment** attachment file name
* **fileDescription** attachment description
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
const txt_file = 'ReadMe.txt';
AsposePdf().then(AsposePdfModule => {
    /*Add attachment to a PDF-file and save the "ResultPdfAddAttachment.pdf"*/
    const json = AsposePdfModule.AsposePdfAddAttachment(pdf_file, txt_file, 'Description', "ResultPdfAddAttachment.pdf");
    console.log("AsposePdfAddAttachment => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
const txt_file = 'ReadMe.txt';
/*Add attachment to a PDF-file and save the "ResultPdfAddAttachment.pdf"*/
const json = AsposePdfModule.AsposePdfAddAttachment(pdf_file, txt_file, 'Description', "ResultPdfAddAttachment.pdf");
console.log("AsposePdfAddAttachment => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```