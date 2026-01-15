---
title: "AsposePdfReplaceTextEx"
second_title: Aspose.PDF for Node.js via C++
description: "Replace text in a PDF-file with alignment control."
type: docs
url: /nodejs-cpp/organize/asposepdfreplacetextex/
---

_Replace text in a PDF-file with alignment control._

```js
function AsposePdfReplaceTextEx(
    fileName,
    findText,
    replaceText,
    options,
    fileNameResult
)
```

**Parameters**: 

* **fileName** file name 
* **findText** text fragment to search
* **replaceText** text fragment to replace
* **options** object, settings for text replacement:
  * `alignment` (string), text alignment (e.g., "left", "right", "auto")
  * `numPages` (string|number|Array), target pages to process:
    * number, page number as 2
    * string, include page numbers with intervals as "7, 20, 22, 30-32, 33, 36-40, 46"
    * Array, array of page numbers, such as [1,3]
  Pass an empty object `{}` for default behavior
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
    const findText = 'Aspose';
    const replaceText = 'ASPOSE';
    const optionsText = {numPages: 1, alignment: "auto"};
    /*Replace text in a PDF-file with alignment control and save the "ResultPdfReplaceTextEx.pdf"*/
    const json = AsposePdfModule.AsposePdfReplaceTextEx(pdf_file, findText, replaceText, optionsText, "ResultPdfReplaceTextEx.pdf");
    console.log("AsposePdfReplaceTextEx => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
const findText = 'Aspose';
const replaceText = 'ASPOSE';
const optionsText = {numPages: 1, alignment: "auto"};
/*Replace text in a PDF-file with alignment control and save the "ResultPdfReplaceTextEx.pdf"*/
const json = AsposePdfModule.AsposePdfReplaceTextEx(pdf_file, findText, replaceText, optionsText, "ResultPdfReplaceTextEx.pdf");
console.log("AsposePdfReplaceTextEx => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```