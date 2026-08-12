---
title: "AsposePdfMerge2Files"
second_title: "C++를 통해 Node.js용 Aspose.PDF"
description: "두 개의 PDF 파일을 병합합니다."
type: docs
url: /ko/nodejs-cpp/organize/asposepdfmerge2files/
---

_두 개의 PDF 파일을 병합합니다._

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
JSON 객체
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