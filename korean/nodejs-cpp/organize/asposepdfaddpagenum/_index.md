---
title: "AsposePdfAddPageNum"
second_title: "C++를 통해 Node.js용 Aspose.PDF"
description: "PDF 파일에 페이지 번호를 추가합니다."
type: docs
url: /ko/nodejs-cpp/organize/asposepdfaddpagenum/
---

_PDF 파일에 페이지 번호를 추가합니다._

```js
function AsposePdfAddPageNum(
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
    /*Add page number to a PDF-file save the "ResultAddPageNum.pdf"*/
    const json = AsposePdfModule.AsposePdfAddPageNum(pdf_file, "ResultAddPageNum.pdf");
    console.log("AsposePdfAddPageNum => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Add page number to a PDF-file and save the "ResultAddPageNum.pdf"*/
const json = AsposePdfModule.AsposePdfAddPageNum(pdf_file, "ResultAddPageNum.pdf");
console.log("AsposePdfAddPageNum => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```