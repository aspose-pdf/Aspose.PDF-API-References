---
title: "AsposePdfExtractText"
second_title: Aspose.PDF for Node.js via C++
description:  "Extract text from a PDF-file."
type: docs
url: /nodejs-cpp/convert/asposepdfextracttext/
---

_Extract text from a PDF-file._

```js
function AsposePdfExtractText(
    fileName 
)
```

**Parameters**: 
  * **fileName** file name 

**Return**: 
JSON object
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **extractText** - text from PDF


**CommonJS**:

```js
const AsposePdf = require('.//AsposePDFforNode.cjs');
const pdf_file = 'ReadMe.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Extract text from a PDF-file*/
    const json = AsposePdfModule.AsposePdfExtractText(pdf_file);
    console.log("AsposePdfExtractText => %O", json.errorCode == 0 ? json.extractText : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from './/AsposePDFforNode.mjs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'ReadMe.pdf';
/*Extract text from a PDF-file*/
const json = AsposePdfModule.AsposePdfExtractText(pdf_file);
console.log("AsposePdfExtractText => %O", json.errorCode == 0 ? json.extractText : json.errorText);
```