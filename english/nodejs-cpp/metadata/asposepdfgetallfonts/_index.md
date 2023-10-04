---
title: "AsposePdfGetAllFonts"
second_title: Aspose.PDF for Node.js via C++
description: "Get list fonts from a PDF-file."
type: docs
url: /nodejs-cpp/metadata/asposepdfgetallfonts/
---

_Get list fonts from a PDF-file._

```js
function AsposePdfGetAllFonts(
    fileName
)
```

**Parameters**: 

* **fileName** file name 

**Return**: 

JSON object 

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **fonts** - array of : 
  * fontName - font name
  * isEmbedded - indicates whether the font is embedded
  * isAccessible - indicating whether the font is present


**CommonJS**:

```js
const AsposePdf = require('.//AsposePDFforNode.cjs');
const pdf_file = 'ReadMe.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Get list fonts from a PDF-file*/
    const json = AsposePdfModule.AsposePdfGetAllFonts(pdf_file);
    /*json.fonts - array of fonts: { fontName: <string>, isEmbedded: <boolean>, isAccessible: <boolean> }*/
    console.log("AsposePdfGetAllFonts => fonts: %O", json.errorCode == 0 ? json.fonts : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from './/AsposePDFforNode.mjs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'ReadMe.pdf';
/*Get list fonts from a PDF-file*/
const json = AsposePdfModule.AsposePdfGetAllFonts(pdf_file);
/*json.fonts - array of fonts: { fontName: <string>, isEmbedded: <boolean>, isAccessible: <boolean> }*/
console.log("AsposePdfGetAllFonts => fonts: %O", json.errorCode == 0 ? json.fonts : json.errorText);
```