---
title: "AsposePdfFindHiddenText"
second_title: "Aspose.PDF untuk Node.js via C++"
description: "Temukan teks tersembunyi dalam PDF-file."
type: docs
url: /id/nodejs-cpp/organize/asposepdffindhiddentext/
---

_Temukan teks tersembunyi dalam file PDF._

```js
function AsposePdfFindHiddenText(
    fileName
)
```

**Parameters**: 

* **fileName** file name

**Return**: 

Objek JSON

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
    /*Find hidden text in a PDF-file*/
    const json = AsposePdfModule.AsposePdfFindHiddenText(pdf_file);
    /*json.textFragments - array of text fragments: { text: <string>, xIndent: <number>, yIndent: <number>, fontName: <string>, fontSize: <number> }*/
    console.log("AsposePdfFindHiddenText => textFragments: %O", json.errorCode == 0 ? json.textFragments : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Find hidden text in a PDF-file*/
const json = AsposePdfModule.AsposePdfFindHiddenText(pdf_file);
/*json.textFragments - array of text fragments: { text: <string>, xIndent: <number>, yIndent: <number>, fontName: <string>, fontSize: <number> }*/
console.log("AsposePdfFindHiddenText => textFragments: %O", json.errorCode == 0 ? json.textFragments : json.errorText);
```