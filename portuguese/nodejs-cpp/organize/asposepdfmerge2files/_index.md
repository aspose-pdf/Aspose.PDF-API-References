---
title: "AsposePdfMerge2Files"
second_title: "Aspose.PDF para Node.js via C++"
description: "Mesclar dois arquivos PDF."
type: docs
url: /pt/nodejs-cpp/organize/asposepdfmerge2files/
---

_Mescle dois PDF-files._

```js
function AsposePdfMerge2Files(
    fileName1,
    fileName2,
    fileNameResult 
)
```

**Parameters**: 
  * **fileName1** file name #1 
  * **fileName2** file name #2 
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
    /*Merge two PDF-files and save the "ResultMerge.pdf"*/
    const json = AsposePdfModule.AsposePdfMerge2Files(pdf_file, pdf_file, "ResultMerge.pdf");
    console.log("AsposePdfMerge2Files => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Merge two PDF-files and save the "ResultMerge.pdf"*/
const json = AsposePdfModule.AsposePdfMerge2Files(pdf_file, pdf_file, "ResultMerge.pdf");
console.log("AsposePdfMerge2Files => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```