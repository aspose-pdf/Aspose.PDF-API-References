---
title: "AsposePdfExtractText"
second_title: "Aspose.PDF per Node.js via C++"
description: "Estrai il testo da un file PDF."
type: docs
url: /it/nodejs-cpp/convert/asposepdfextracttext/
---

_Estrai il testo da un file PDF._

```js
function AsposePdfExtractText(
    fileName 
)
```

**Parameters**: 
  * **fileName** file name 

**Return**: 
Oggetto JSON
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