---
title: "AsposePdfTablesToCSV"
second_title: "Aspose.PDF för Node.js via C++"
description: "Konvertera en PDF-fil till CSV (extrahera tabeller)."
type: docs
url: /sv/nodejs-cpp/convert/asposepdftablestocsv/
---

_Konvertera en PDF-fil till CSV (extrahera tabeller)._

```
function AsposePdfTablesToCSV(
    fileName,
    fileNameResult,
    delimiter
)
```

**Parameters**: 
  * **fileName** file name 
  * **fileNameResult** result file name template (for sample: "ResultPdfTablesToCSV{0:D2}.csv" where {0}, {0:D2}, {0:D3}, {0:Dn} - format page number) 
  * **delimiter** delimiter for csv (comma-separated value), default ";"

**Return**: 
JSON-objekt
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **filesCount** - csv files count
  * **filesNameResult** - array of result filenames


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Convert a PDF-file to CSV (extract tables) with template "ResultPdfTablesToCSV{0:D2}.csv" ({0}, {0:D2}, {0:D3}, ... format page number), TAB as delimiter and save*/
    const json = AsposePdfModule.AsposePdfTablesToCSV(pdf_file, "ResultPdfTablesToCSV{0:D2}.csv", "\t");
    console.log("AsposePdfTablesToCSV => %O", json.errorCode == 0 ? json.filesNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Convert a PDF-file to CSV (extract tables) with template "ResultPdfTablesToCSV{0:D2}.csv" ({0}, {0:D2}, {0:D3}, ... format page number), TAB as delimiter and save*/
const json = AsposePdfModule.AsposePdfTablesToCSV(pdf_file, "ResultPdfTablesToCSV{0:D2}.csv", "\t");
console.log("AsposePdfTablesToCSV => %O", json.errorCode == 0 ? json.filesNameResult : json.errorText);
```