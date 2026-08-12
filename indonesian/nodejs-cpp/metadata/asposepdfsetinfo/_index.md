---
title: "AsposePdfSetInfo"
second_title: "Aspose.PDF untuk Node.js via C++"
description: "Atur info (metadata) dalam file PDF."
type: docs
url: /id/nodejs-cpp/metadata/asposepdfsetinfo/
---

_Setel info (metadata) dalam file PDF._

```js
function AsposePdfSetInfo(
    fileName,
    title, 
    creator, 
    author,
    subject,
    keywords,
    creation,
    mod,
    fileNameResult
)
```

**Parameters**: 

* **fileName** file name 
* **title** title
* **creator** creator
* **author** author
* **subject** subject
* **keywords** list keywords
* **creation** creation date
* **mod** modify date
* **fileNameResult** result file name

Untuk 'title', 'creator', 'author', 'subject', 'keywords', 'creation', dan 'mod', jika tidak perlu mengatur nilai, gunakan undefined atau "" (string kosong)

**Return**: 

Objek JSON

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Set PDF info: title, creator, author, subject, keywords, creation (date), mod (date modify)*/
    /*If not need to set value, use undefined or "" (empty string)*/
    /*Set info (metadata) in a PDF-file and save the "ResultSetInfo.pdf"*/
    const json = AsposePdfModule.AsposePdfSetInfo(pdf_file, "Setting PDF Document Information", "", "Aspose", undefined, "Aspose.Pdf, DOM, API", undefined, "05/05/2023 11:55 PM", "ResultSetInfo.pdf");
    console.log("AsposePdfSetInfo => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Set PDF info: title, creator, author, subject, keywords, creation (date), mod (date modify)*/
/*If not need to set value, use undefined or "" (empty string)*/
/*Set info (metadata) in a PDF-file and save the "ResultSetInfo.pdf"*/
const json = AsposePdfModule.AsposePdfSetInfo(pdf_file, "Setting PDF Document Information", "", "Aspose", undefined, "Aspose.Pdf, DOM, API", undefined, "05/05/2023 11:55 PM", "ResultSetInfo.pdf");
console.log("AsposePdfSetInfo => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```