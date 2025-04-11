---
title: "AsposePdfAddStampPages"
second_title: Aspose.PDF for Node.js via C++
description: "Add stamp to specific pages in a PDF-file."
type: docs
url: /nodejs-cpp/organize/asposepdfaddstamppages/
---

_Add stamp to specific pages in a PDF-file._

```js
function AsposePdfAddStampPages(
    fileName,
    fileStamp,
    setBackground,
    setXIndent,
    setYIndent,
    setHeight,
    setWidth,
    rotation,
    setOpacity,
    numPages,
    fileNameResult
)
```

**Parameters**:

* **fileName** file name 
* **fileStamp** stamp (image) file name 
* **setBackground** background (1 or 0) 
* **setXIndent** x indent stamp 
* **setYIndent** y indent stamp 
* **setHeight** height stamp 
* **setWidth** width stamp 
* **rotation** stamp rotation:
  * Module.Rotation.None
  * Module.Rotation.on90
  * Module.Rotation.on180
  * Module.Rotation.on270 
* **setOpacity** opacity stamp (decimal) 
* **numPages** page numbers:
  * string, include page numbers with intervals as "7, 20, 22, 30-32, 33, 36-40, 46"
  * array, array of page numbers, such as [1,3]
  * number, page number as 2
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
const stamp_file = 'Aspose.jpg';
AsposePdf().then(AsposePdfModule => {
    /*Add stamp to a PDF-file on page #1 and save the "ResultAddStampPages.pdf"*/
    const json = AsposePdfModule.AsposePdfAddStampPages(pdf_file, stamp_file, 0, 15, 15, 50, 50, AsposePdfModule.Rotation.on90, 0.7, 1, "ResultAddStampPages.pdf");
    console.log("AsposePdfAddStampPages => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
const stamp_file = 'Aspose.jpg';
/*Add stamp to a PDF-file page #1 and save the "ResultAddStampPages.pdf"*/
const json = AsposePdfModule.AsposePdfAddStampPages(pdf_file, stamp_file, 0, 15, 15, 50, 50, AsposePdfModule.Rotation.on90, 0.7, 1, "ResultAddStampPages.pdf");
console.log("AsposePdfAddStampPages => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```