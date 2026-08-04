---
title: "AsposePdfToPptX"
second_title: "Aspose.PDF for Node.js via C++"
description: "Конвертировать PDF-файл в PptX."
type: docs
url: /ru/nodejs-cpp/convert/asposepdftopptx/
---

_Преобразовать PDF-файл в PptX._

```js
function AsposePdfToPptX(
    fileName,
    fileNameResult 
)
```

**Parameters**: 

* **fileName** file name 
* **fileNameResult** result file name 

**Return**: 
Объект JSON
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Convert a PDF-file to PptX and save the "ResultPDFtoPptX.pptx"*/
    const json = AsposePdfModule.AsposePdfToPptX(pdf_file, "ResultPDFtoPptX.pptx");
    console.log("AsposePdfToPptX => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Convert a PDF-file to PptX and save the "ResultPDFtoPptX.pptx"*/
const json = AsposePdfModule.AsposePdfToPptX(pdf_file, "ResultPDFtoPptX.pptx");
console.log("AsposePdfToPptX => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```