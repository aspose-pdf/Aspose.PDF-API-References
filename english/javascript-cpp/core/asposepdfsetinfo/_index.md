---
title: "AsposePdfSetInfo"
second_title: Aspose.PDF for JavaScript via C++
description: "Set info (metadata) in PDF file."
type: docs
url: /javascript-cpp/core/asposepdfsetinfo/
---

_Set info (metadata) in PDF file._

```js
function AsposePdfSetInfo(
    fileBlob ,
    fileName ,
    title , 
    creator , 
    author ,
    subject ,
    keywords ,
    creation ,
    mod ,
    fileNameResult
)
```

**Parameters**: 

* **fileBlob** Blob object 
* **fileName** file name 
* **title** title
* **creator** creator
* **author** author
* **subject** subject
* **keywords** list keywords
* **creation** creation date
* **mod** modify date
* **fileResultName** result file name

For 'title', 'creator', 'author', 'subject', 'keywords', 'creation' and 'mod', if not need to set value, use undefined or "" (empty string)

**Return**: 

JSON object 

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **fileNameResult** - result file name


**Example**:

```js
  var ffilePdfSetInfo = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*Set info (metadata) in PDF file.*/
      /*Set PDF info: title, creator, author, subject, keywords, creation (date), mod (date modify)*/
      /*if not need to set value, use undefined or "" (empty string)*/
      /*set info a PDF-file and save the "ResultSetInfo.pdf"*/
      const json = AsposePdfSetInfo(event.target.result, e.target.files[0].name, "Setting PDF Document Information", "", "Aspose", undefined, "Aspose.Pdf, DOM, API", undefined, "16/02/2023 11:55 PM", "ResultSetInfo.pdf");
      if (json.errorCode == 0) document.getElementById('output').textContent = json.fileNameResult;
      else document.getElementById('output').textContent = json.errorText;
      /*make a link to download the result file*/
      DownloadFile(json.fileNameResult, "application/pdf");
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```

