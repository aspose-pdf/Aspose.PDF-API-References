---
title: "AsposePdfEmbedFonts"
second_title: "C++를 통해 Node.js용 Aspose.PDF"
description: "PDF 파일에 글꼴을 포함합니다."
type: docs
url: /ko/nodejs-cpp/organize/asposepdfembedfonts/
---

_PDF 파일에 글꼴을 삽입합니다._

```js
function AsposePdfEmbedFonts(
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
    /*Embed fonts a PDF-file and save the "ResultEmbedFonts.pdf"*/
    const json = AsposePdfModule.AsposePdfEmbedFonts(pdf_file, "ResultEmbedFonts.pdf");
    console.log("AsposePdfEmbedFonts => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Embed fonts a PDF-file and save the "ResultEmbedFonts.pdf"*/
const json = AsposePdfModule.AsposePdfEmbedFonts(pdf_file, "ResultEmbedFonts.pdf");
console.log("AsposePdfEmbedFonts => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```