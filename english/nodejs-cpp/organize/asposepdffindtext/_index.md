---
title: "AsposePdfFindText"
second_title: Aspose.PDF for Node.js via C++
description: "Find text in a PDF-file."
type: docs
url: /nodejs-cpp/organize/asposepdffindtext/
---

_Find text in a PDF-file._

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

JSON object 

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
const AsposePdf = require('.//AsposePDFforNode.cjs');
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
import AsposePdf from './/AsposePDFforNode.mjs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
const findText = 'Aspose';
/*Find text in a PDF-file*/
const json = AsposePdfModule.AsposePdfFindText(pdf_file, findText);
/*json.textFragments - array of text fragments: { text: <string>, xIndent: <number>, yIndent: <number>, fontName: <string>, fontSize: <number> }*/
console.log("AsposePdfFindText => textFragments: %O", json.errorCode == 0 ? json.textFragments : json.errorText);
```