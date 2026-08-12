---
title: "AsposePdfGetAllFonts"
second_title: "Aspose.PDF 用于 Node.js via C++"
description: "获取 PDF 文件的字体列表。"
type: docs
url: /zh/nodejs-cpp/metadata/asposepdfgetallfonts/
---

_获取 PDF 文件中的字体列表。_

```js
function AsposePdfGetAllFonts(
    fileName
)
```

**Parameters**: 

* **fileName** file name 

**Return**: 

JSON 对象

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