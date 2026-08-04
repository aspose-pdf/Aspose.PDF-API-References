---
title: "AsposePdfSetInfo"
second_title: "C++를 통해 Node.js용 Aspose.PDF"
description: "PDF 파일에 정보(메타데이터)를 설정합니다."
type: docs
url: /ko/nodejs-cpp/metadata/asposepdfsetinfo/
---

_PDF 파일에 정보(메타데이터)를 설정합니다._

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

'title', 'creator', 'author', 'subject', 'keywords', 'creation' 및 'mod'에 대해 값을 설정할 필요가 없으면 undefined 또는 ""(빈 문자열)을 사용하십시오.

**Return**: 

JSON 객체

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