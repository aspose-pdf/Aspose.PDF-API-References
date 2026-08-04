---
title: "AsposePdfExtractText"
second_title: "Aspose.PDF لـ Node.js عبر C++"
description: "استخراج النص من ملف PDF."
type: docs
url: /ar/nodejs-cpp/convert/asposepdfextracttext/
---

_استخراج النص من ملف PDF._

```js
function AsposePdfExtractText(
    fileName 
)
```

**Parameters**: 
  * **fileName** file name 

**Return**: 
كائن JSON
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **extractText** - text from PDF


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Extract text from a PDF-file*/
    const json = AsposePdfModule.AsposePdfExtractText(pdf_file);
    console.log("AsposePdfExtractText => %O", json.errorCode == 0 ? json.extractText : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Extract text from a PDF-file*/
const json = AsposePdfModule.AsposePdfExtractText(pdf_file);
console.log("AsposePdfExtractText => %O", json.errorCode == 0 ? json.extractText : json.errorText);
```