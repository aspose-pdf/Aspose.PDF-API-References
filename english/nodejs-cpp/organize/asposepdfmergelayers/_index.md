---
title: "AsposePdfMergeLayers"
second_title: Aspose.PDF for Node.js via C++
description: "Merge layers a PDF-file."
type: docs
url: /nodejs-cpp/organize/asposepdfmergelayers/
---

_Merge layers a PDF-file._

```js
function AsposePdfMergeLayers(
    fileName,
    newLayerName,
    fileNameResult
)
```

**Parameters**: 

* **fileName** file name 
* **newLayerName** merged layer name for each page
* **fileNameResult** result file name 

**Return**: 
JSON object 
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    const mergedLayerName = 'MergedLayer';
    /*Merge layers a PDF-file and save the "ResultPdfMergeLayers.pdf"*/
    const json = AsposePdfModule.AsposePdfMergeLayers(pdf_file, mergedLayerName, "ResultPdfMergeLayers.pdf");
    console.log("AsposePdfMergeLayers => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
const mergedLayerName = 'MergedLayer';
/*Merge layers a PDF-file and save the "ResultPdfMergeLayers.pdf"*/
const json = AsposePdfModule.AsposePdfMergeLayers(pdf_file, mergedLayerName, "ResultPdfMergeLayers.pdf");
console.log("AsposePdfMergeLayers => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```