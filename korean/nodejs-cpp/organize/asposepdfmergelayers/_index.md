---
title: "AsposePdfMergeLayers"
second_title: "C++를 통해 Node.js용 Aspose.PDF"
description: "PDF 파일의 레이어를 병합합니다."
type: docs
url: /ko/nodejs-cpp/organize/asposepdfmergelayers/
---

_PDF 파일의 레이어를 병합합니다._

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
JSON 객체
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