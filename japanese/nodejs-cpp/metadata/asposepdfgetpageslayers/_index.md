---
title: "AsposePdfGetPagesLayers"
second_title: "C++ 経由で Node.js 用 Aspose.PDF"
description: "PDFファイルからレイヤーの一覧を取得します。"
type: docs
url: /ja/nodejs-cpp/metadata/asposepdfgetpageslayers/
---

_PDF ファイルからレイヤーの一覧を取得します。_

```js
function AsposePdfGetPagesLayers(
    fileName
)
```

**Parameters**: 

* **fileName** file name 

**Return**: 

JSON オブジェクト

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **pagesLayers[][]** - list of pages with lists of layers on each page


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Get list layers from a PDF-file*/
    const json = AsposePdfModule.AsposePdfGetPagesLayers(pdf_file);
    /*json.pagesLayers - list of pages with lists of layers on each page*/
    console.log("AsposePdfGetPagesLayers => layers: %O", json.errorCode == 0 ? json.pagesLayers : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Get list layers from a PDF-file*/
const json = AsposePdfModule.AsposePdfGetPagesLayers(pdf_file);
/*json.pagesLayers - list of pages with lists of layers on each page*/
console.log("AsposePdfGetPagesLayers => layers: %O", json.errorCode == 0 ? json.pagesLayers : json.errorText);
```