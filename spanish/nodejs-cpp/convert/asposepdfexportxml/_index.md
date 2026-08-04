---
title: "AsposePdfExportXml"
second_title: "Aspose.PDF para Node.js via C++"
description: "Exportar desde un archivo PDF con AcroForm a XML."
type: docs
url: /es/nodejs-cpp/convert/asposepdfexportxml/
---

_Exportar desde un archivo PDF con AcroForm a XML._

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
Objeto JSON
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