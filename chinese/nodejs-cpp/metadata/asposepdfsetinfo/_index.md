---
title: "AsposePdfSetInfo"
second_title: "Aspose.PDF 用于 Node.js via C++"
description: "在 PDF 文件中设置信息（元数据）。"
type: docs
url: /zh/nodejs-cpp/metadata/asposepdfsetinfo/
---

_在 PDF 文件中设置信息（元数据）。_

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

对于 'title'、'creator'、'author'、'subject'、'keywords'、'creation' 和 'mod'，如果不需要设置值，请使用 undefined 或 ""（空字符串）。

**Return**: 

JSON 对象

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