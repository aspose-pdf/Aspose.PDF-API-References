---
title: "AsposePdfConvertToGrayscale"
second_title: "Aspose.PDF para Node.js via C++"
description: "Converter um arquivo PDF para escala de cinza."
type: docs
url: /pt/nodejs-cpp/convert/asposepdfconverttograyscale/
---

_Converter um arquivo PDF para escala de cinza._

```js
function AsposePdfConvertToGrayscale(
    fileName,
    fileNameResult 
)
```

**Parameters**: 

* **fileName** file name 
* **fileNameResult** result file name 

**Return**: 
Objeto JSON
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Convert a PDF-file to grayscale and save the "ResultConvertToGrayscale.pdf"*/
    const json = AsposePdfModule.AsposePdfConvertToGrayscale(pdf_file, "ResultConvertToGrayscale.pdf");
    console.log("AsposePdfConvertToGrayscale => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Convert a PDF-file to grayscale and save the "ResultConvertToGrayscale.pdf"*/
const json = AsposePdfModule.AsposePdfConvertToGrayscale(pdf_file, "ResultConvertToGrayscale.pdf");
console.log("AsposePdfConvertToGrayscale => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```