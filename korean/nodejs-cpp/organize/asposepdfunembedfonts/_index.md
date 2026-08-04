---
title: "AsposePdfUnembedFonts"
second_title: "C++를 통해 Node.js용 Aspose.PDF"
description: "PDF 파일에서 글꼴 포함을 해제합니다."
type: docs
url: /ko/nodejs-cpp/organize/asposepdfunembedfonts/
---

_PDF 파일에서 글꼴을 삽입 해제합니다._

```js
function AsposePdfUnembedFonts(
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
    /*Unembed fonts a PDF-file and save the "ResultUnembedFonts.pdf"*/
    const json = AsposePdfModule.AsposePdfUnembedFonts(pdf_file, "ResultUnembedFonts.pdf");
    console.log("AsposePdfUnembedFonts => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Unembed fonts a PDF-file and save the "ResultUnembedFonts.pdf"*/
const json = AsposePdfModule.AsposePdfUnembedFonts(pdf_file, "ResultUnembedFonts.pdf");
console.log("AsposePdfUnembedFonts => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```