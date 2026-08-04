---
title: "AsposePdfAddTextHeaderFooter"
second_title: "C++를 통해 Node.js용 Aspose.PDF"
description: "PDF 파일의 머리글/바닥글에 텍스트를 추가합니다."
type: docs
url: /ko/nodejs-cpp/organize/asposepdfaddtextheaderfooter/
---

_PDF 파일의 헤더/푸터에 텍스트를 추가합니다._

```js
function AsposePdfAddTextHeaderFooter(
    fileName,
    header, 
    footer,
    fileNameResult
)
```

**Parameters**: 

* **fileName** file name 
* **header** page header, if not need to set, use undefined or "" (empty string)
* **footer** page footer, if not need to set, use undefined or "" (empty string)
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
    /*Add text in Header/Footer of a PDF-file and save the "ResultAddHeaderFooter.pdf"*/
    const json = AsposePdfModule.AsposePdfAddTextHeaderFooter(pdf_file, "Aspose.PDF for Node.js via C++ via C++", "ASPOSE", "ResultAddHeaderFooter.pdf");
    console.log("AsposePdfAddTextHeaderFooter => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Add text in Header/Footer of a PDF-file and save the "ResultAddHeaderFooter.pdf"*/
const json = AsposePdfModule.AsposePdfAddTextHeaderFooter(pdf_file, "Aspose.PDF for Node.js via C++ via C++", "ASPOSE", "ResultAddHeaderFooter.pdf");
console.log("AsposePdfAddTextHeaderFooter => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```