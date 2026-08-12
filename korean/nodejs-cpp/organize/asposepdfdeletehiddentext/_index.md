---
title: "AsposePdfDeleteHiddenText"
second_title: "C++를 통해 Node.js용 Aspose.PDF"
description: "PDF 파일에서 숨겨진 텍스트를 삭제합니다."
type: docs
url: /ko/nodejs-cpp/organize/asposepdfdeletehiddentext/
---

_PDF 파일에서 숨겨진 텍스트를 삭제합니다._

```js
function AsposePdfDeleteHiddenText(
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
    /*Delete hidden text from a PDF-file and save the "ResultPdfDeleteHiddenText.pdf"*/
    const json = AsposePdfModule.AsposePdfDeleteHiddenText(pdf_file, "ResultPdfDeleteHiddenText.pdf");
    console.log("AsposePdfDeleteHiddenText => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Delete hidden text from a PDF-file and save the "ResultPdfDeleteHiddenText.pdf"*/
const json = AsposePdfModule.AsposePdfDeleteHiddenText(pdf_file, "ResultPdfDeleteHiddenText.pdf");
console.log("AsposePdfDeleteHiddenText => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```