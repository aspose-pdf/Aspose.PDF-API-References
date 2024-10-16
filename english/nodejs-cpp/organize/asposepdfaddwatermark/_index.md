---
title: "AsposePdfAddWatermark"
second_title: Aspose.PDF for Node.js via C++
description: "Add watermark to a PDF-file."
type: docs
url: /nodejs-cpp/organize/asposepdfaddwatermark/
---

_Add watermark to a PDF-file._

```js
function AsposePdfAddWatermark(
    fileName,
    text,
    fontName,
    fontSize,
    foregroundColor,
    xPosition,
    yPosition,
    rotation,
    isBackground,
    opacity,
    fileNameResult 
)
```

**Parameters**:

* **fileName** file name
* **text** watermark text
* **fontName** font name
* **fontSize** font size
* **foregroundColor** text color (hexadecimal format "#RRGGBB", where RR-red, GG-green and BB-blue hexadecimal integers)
* **xPosition** x watermark position
* **yPosition** y watermark position
* **rotation** watermark rotation (0-360)
* **isBackground** background (1 or 0)
* **opacity** opacity (decimal)
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
    /*Add watermark to a PDF-file and save the "ResultWatermark.pdf"*/
    const json = AsposePdfModule.AsposePdfAddWatermark(pdf_file, "Aspose PDF", "Arial", 32, "#010101", 100, 100, 45, 1, 0.5, "ResultAddWatermark.pdf");
    console.log("AsposePdfAddWatermark => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Add watermark to a PDF-file and save the "ResultWatermark.pdf"*/
const json = AsposePdfModule.AsposePdfAddWatermark(pdf_file, "Aspose PDF", "Arial", 32, "#010101", 100, 100, 45, 1, 0.5, "ResultAddWatermark.pdf");
console.log("AsposePdfAddWatermark => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```