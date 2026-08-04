---
title: "AsposePdfFindText"
second_title: "C++를 통해 Node.js용 Aspose.PDF"
description: "PDF 파일에서 텍스트를 찾습니다."
type: docs
url: /ko/nodejs-cpp/organize/asposepdffindtext/
---

_PDF 파일에서 텍스트를 찾습니다._

```js
function AsposePdfFindText(
    fileName,
    findText
)
```

**Parameters**: 

* **fileName** file name
* **findText** text fragment to search

**Return**: 

JSON 객체

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **textFragments** - array of :
  * text - text fragment
  * xIndent - X coordinate
  * yIndent - Y coordinate
  * fontName - font name
  * fontSize - font size


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    const findText = 'Aspose';
    /*Find text in a PDF-file*/
    const json = AsposePdfModule.AsposePdfFindText(pdf_file, findText);
    /*json.textFragments - array of text fragments: { text: <string>, xIndent: <number>, yIndent: <number>, fontName: <string>, fontSize: <number> }*/
    console.log("AsposePdfFindText => textFragments: %O", json.errorCode == 0 ? json.textFragments : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
const findText = 'Aspose';
/*Find text in a PDF-file*/
const json = AsposePdfModule.AsposePdfFindText(pdf_file, findText);
/*json.textFragments - array of text fragments: { text: <string>, xIndent: <number>, yIndent: <number>, fontName: <string>, fontSize: <number> }*/
console.log("AsposePdfFindText => textFragments: %O", json.errorCode == 0 ? json.textFragments : json.errorText);
```