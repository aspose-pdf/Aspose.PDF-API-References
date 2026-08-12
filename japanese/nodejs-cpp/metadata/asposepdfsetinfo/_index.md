---
title: "AsposePdfSetInfo"
second_title: "C++ 経由で Node.js 用 Aspose.PDF"
description: "PDFファイルに情報（メタデータ）を設定します。"
type: docs
url: /ja/nodejs-cpp/metadata/asposepdfsetinfo/
---

_PDF ファイルに情報 (メタデータ) を設定します。_

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

「title」「creator」「author」「subject」「keywords」「creation」「mod」のいずれかの値を設定する必要がない場合は、undefined または ""（空文字列）を使用してください。

**Return**: 

JSON オブジェクト

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