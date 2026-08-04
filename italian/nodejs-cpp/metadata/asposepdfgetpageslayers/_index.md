---
title: "AsposePdfGetPagesLayers"
second_title: "Aspose.PDF per Node.js via C++"
description: "Ottieni l'elenco dei layer da un file PDF."
type: docs
url: /it/nodejs-cpp/metadata/asposepdfgetpageslayers/
---

_Ottieni l'elenco dei layer da un file PDF._

```js
function AsposePdfGetPagesLayers(
    fileName
)
```

**Parameters**: 

* **fileName** file name 

**Return**: 

Oggetto JSON

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