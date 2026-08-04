---
title: "AsposePdfGetPagesLayers"
second_title: "C++를 통해 Node.js용 Aspose.PDF"
description: "PDF 파일에서 레이어 목록을 가져옵니다."
type: docs
url: /ko/nodejs-cpp/metadata/asposepdfgetpageslayers/
---

_PDF 파일에서 레이어 목록을 가져옵니다._

```js
function AsposePdfGetPagesLayers(
    fileName
)
```

**Parameters**: 

* **fileName** file name 

**Return**: 

JSON 객체

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