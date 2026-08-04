---
title: "AsposePdfExtractText"
second_title: "C++를 통해 Node.js용 Aspose.PDF"
description: "PDF 파일에서 텍스트를 추출합니다."
type: docs
url: /ko/nodejs-cpp/convert/asposepdfextracttext/
---

_PDF 파일에서 텍스트를 추출합니다._

```js
function AsposePdfExtractText(
    fileName 
)
```

**Parameters**: 
  * **fileName** file name 

**Return**: 
JSON 객체
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **extractText** - text from PDF


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Extract text from a PDF-file*/
    const json = AsposePdfModule.AsposePdfExtractText(pdf_file);
    console.log("AsposePdfExtractText => %O", json.errorCode == 0 ? json.extractText : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Extract text from a PDF-file*/
const json = AsposePdfModule.AsposePdfExtractText(pdf_file);
console.log("AsposePdfExtractText => %O", json.errorCode == 0 ? json.extractText : json.errorText);
```