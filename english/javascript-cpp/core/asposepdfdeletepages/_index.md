---
title: "AsposePdfDeletePages"
second_title: Aspose.PDF for JavaScript via C++
description: "Delete pages from PDF file."
type: docs
url: /javascript-cpp/core/asposepdfdeletepages/
---

_Delete pages from PDF file._

```js
function AsposePdfDeletePages(
    fileBlob,
    fileName,
    fileResultName,
    numPages
)
```

**Parameters**: 

* **fileBlob** Blob object 
* **fileName** file name 
* **fileResultName** result file name
* **numPages** page numbers:
  * string, include page numbers with intervals as "7, 20, 22, 30-32, 33, 36-40, 46"
  * array, array of page numbers, such as [1,3]
  * number, page number as 2

**Return**: 

JSON object 

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **fileNameResult** - result file name


**Example**:

```js
  var ffileDeletePages = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*delete 1-3 pages a PDF-file and save the "ResultOptimize.pdf"*/
      const json = AsposePdfDeletePages(event.target.result, e.target.files[0].name, "ResultDeletePages.pdf", "1-3");
      if (json.errorCode == 0) document.getElementById('output').textContent = json.fileNameResult;
      else document.getElementById('output').textContent = json.errorText;
      /*make a link to download the result file*/
      DownloadFile(json.fileNameResult, "application/pdf");
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```

