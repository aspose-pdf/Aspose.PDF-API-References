---
title: "AsposePdfGetInfo"
second_title: Aspose.PDF for JavaScript via C++
description: "Get info (metadata) from PDF file."
type: docs
url: /javascript-cpp/core/asposepdfgetinfo/
---

_Get info (metadata) from PDF file._

```js
function AsposePdfGetInfo(
    fileBlob,
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
* **title** - title
* **creator** - creator
* **author** - author
* **subject** - subject
* **keywords** - keywords
* **creation** - creation date
* **mod** - modify date


**Example**:

```js
  var ffilePdfGetInfo = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*Get info (metadata) from PDF file.*/
      const json = AsposePdfGetInfo(event.target.result, e.target.files[0].name);
      if (json.errorCode == 0) document.getElementById('output').textContent = "JSON:\n" + JSON.stringify(json, null, 4);
      else document.getElementById('output').textContent = json.errorText;
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```

