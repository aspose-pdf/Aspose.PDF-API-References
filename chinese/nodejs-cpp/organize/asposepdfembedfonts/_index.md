---
title: "AsposePdfEmbedFonts"
second_title: "Aspose.PDF 用于 Node.js via C++"
description: "在 PDF 文件中嵌入字体。"
type: docs
url: /zh/nodejs-cpp/organize/asposepdfembedfonts/
---

_在 PDF 文件中嵌入字体。_

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
JSON 对象
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