---
title: "AsposePdfAddStamp"
second_title: Aspose.PDF for Node.js via C++
description: "Add stamp to a PDF-file."
type: docs
url: /nodejs-cpp/organize/asposepdfaddstamp/
---

_Add stamp to a PDF-file._

```js
function AsposePdfAddStamp(
    fileName,
    fileStamp,
    setBackground,
    setXIndent,
    setYIndent,
    setHeight,
    setWidth,
    rotation,
    setOpacity,
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
* **fileNameResult** result file name 

**Return**:

JSON object

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('.//AsposePDFforNode.cjs');
const pdf_file = 'Aspose.pdf';
const stamp_file = 'Aspose.jpg';
AsposePdf().then(AsposePdfModule => {
    /*Add stamp to a PDF-file and save the "ResultImage.pdf"*/
    const json = AsposePdfModule.AsposePdfAddStamp(pdf_file, stamp_file, 0, 5, 5, 40, 40, AsposePdfModule.Rotation.on270, 0.5, "ResultAddStamp.pdf");
    console.log("AsposePdfAddStamp => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from './/AsposePDFforNode.mjs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
const stamp_file = 'Aspose.jpg';
/*Add stamp to a PDF-file and save the "ResultImage.pdf"*/
const json = AsposePdfModule.AsposePdfAddStamp(pdf_file, stamp_file, 0, 5, 5, 40, 40, AsposePdfModule.Rotation.on270, 0.5, "ResultAddStamp.pdf");
console.log("AsposePdfAddStamp => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```