---
title: "AsposePdfGetAttachment"
second_title: "C++를 통해 Node.js용 Aspose.PDF"
description: "PDF 파일에서 첨부 파일을 가져옵니다."
type: docs
url: /ko/nodejs-cpp/organize/asposepdfgetattachment/
---

_PDF 파일에서 첨부 파일을 가져옵니다._

```js
function AsposePdfGetAttachment(
    fileName,
    fileNameResult
)
```

**Parameters**: 
  * **fileName** file name 
  * **fileNameResult** result file name template (for sample: "ResultPdfGetAttachment_{0}" where {0} - name of attachment) 

**Return**: 
JSON 객체
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **filesCount** - attachment files count
  * **filesNameResult** - array of result filenames


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Get attachment from a PDF-file and save with template "ResultPdfGetAttachment_{0}" ({0} - name of attachment)*/
    const json = AsposePdfModule.AsposePdfGetAttachment(pdf_file, "ResultPdfGetAttachment_{0}");
    console.log("AsposePdfGetAttachment => %O", json.errorCode == 0 ? json.filesNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Get attachment from a PDF-file and save with template "ResultPdfGetAttachment_{0}" ({0} - name of attachment)*/
const json = AsposePdfModule.AsposePdfGetAttachment(pdf_file, "ResultPdfGetAttachment_{0}");
console.log("AsposePdfGetAttachment => %O", json.errorCode == 0 ? json.filesNameResult : json.errorText);
```