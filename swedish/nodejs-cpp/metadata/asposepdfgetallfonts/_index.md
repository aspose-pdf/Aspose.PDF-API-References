---
title: "AsposePdfGetAllFonts"
second_title: "Aspose.PDF för Node.js via C++"
description: "Hämta lista över teckensnitt från en PDF-fil."
type: docs
url: /sv/nodejs-cpp/metadata/asposepdfgetallfonts/
---

_Hämta lista med teckensnitt från en PDF-fil._

```js
function AsposePdfGetAllFonts(
    fileName
)
```

**Parameters**: 

* **fileName** file name 

**Return**: 

JSON-objekt

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **fonts** - array of : 
  * fontName - font name
  * isEmbedded - indicates whether the font is embedded
  * isAccessible - indicating whether the font is present


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Get list fonts from a PDF-file*/
    const json = AsposePdfModule.AsposePdfGetAllFonts(pdf_file);
    /*json.fonts - array of fonts: { fontName: <string>, isEmbedded: <boolean>, isAccessible: <boolean> }*/
    console.log("AsposePdfGetAllFonts => fonts: %O", json.errorCode == 0 ? json.fonts : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Get list fonts from a PDF-file*/
const json = AsposePdfModule.AsposePdfGetAllFonts(pdf_file);
/*json.fonts - array of fonts: { fontName: <string>, isEmbedded: <boolean>, isAccessible: <boolean> }*/
console.log("AsposePdfGetAllFonts => fonts: %O", json.errorCode == 0 ? json.fonts : json.errorText);
```