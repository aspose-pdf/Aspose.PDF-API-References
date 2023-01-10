---
title: "AsposePdfExtractText"
second_title: Aspose.PDF for JavaScript via C++
description:  "Extract text from PDF file."
type: docs
url: /javascript-cpp/core/asposepdfextracttext/
---

_Extract text from PDF file._

```js
function AsposePdfExtractText(
    fileBlob ,
    fileName 
)
```

**Parameters**: 
  * **fileBlob** Blob object 
  * **fileName** file name 

**Return**: 
JSON object
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **extractText** - text from PDF

**Example**:
```js
  var ffileExtract = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*Extarct text from a PDF-file*/
      const json = AsposePdfExtractText(event.target.result, e.target.files[0].name);
      if (json.errorCode == 0) document.getElementById('output').textContent = json.extractText;
      else document.getElementById('output').textContent = json.errorText;
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```

