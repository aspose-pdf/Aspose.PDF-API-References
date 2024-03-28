---
title: "AsposePdfExportXml"
second_title: Aspose.PDF for Node.js via C++
description:  "Export from a PDF-file with AcroForm to XML."
type: docs
url: /nodejs-cpp/convert/asposepdfexportxml/
---

_Export from a PDF-file with AcroForm to XML._

```js
function AsposePdfExportXml(
    fileName,
    fileNameResult 
)
```

**Parameters**: 

* **fileName** file name 
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
    /*Export from a PDF-file with AcroForm to XML and save the "ResultPdfExportXml.xml"*/
    const json = AsposePdfModule.AsposePdfExportXml(pdf_file, "ResultPdfExportXml.xml");
    console.log("AsposePdfExportXml => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Export from a PDF-file with AcroForm to XML and save the "ResultPdfExportXml.xml"*/
const json = AsposePdfModule.AsposePdfExportXml(pdf_file, "ResultPdfExportXml.xml");
console.log("AsposePdfExportXml => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```