---
title: "AsposePdfAddTextHeaderFooter"
second_title: Aspose.PDF for JavaScript via C++
description: "Add text in Header/Footer of PDF file."
type: docs
url: /javascript-cpp/core/asposepdfaddtextheaderfooter/
---

_Add text in Header/Footer of PDF file._

```js
function AsposePdfAddTextHeaderFooter(
    fileBlob ,
    fileName ,
    header , 
    footer ,
    fileResultName
)
```

**Parameters**: 

* **fileBlob** Blob object 
* **fileName** file name 
* **header** page header, if not need to set, use undefined or "" (empty string)
* **footer** page footer, if not need to set, use undefined or "" (empty string)
* **fileResultName** result file name 

**Return**: 

JSON object 

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **fileNameResult** - result file name


**Example**:

```js
  var ffileAddTextHeaderFooter = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*add page header a PDF-file and save the "ResultAddHeader.pdf"*/
      const json = AsposePdfAddTextHeaderFooter(event.target.result, e.target.files[0].name, "Aspose.PDF for JavaScript via C++", "", "ResultAddHeader.pdf");
      if (json.errorCode == 0) document.getElementById('output').textContent = json.fileNameResult;
      else document.getElementById('output').textContent = json.errorText;
      /*make a link to download the result file*/
      DownloadFile(json.fileNameResult, "application/pdf");
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```

