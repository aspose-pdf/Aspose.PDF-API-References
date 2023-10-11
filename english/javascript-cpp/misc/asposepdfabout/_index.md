---
title: "AsposePdfAbout"
second_title: Aspose.PDF for JavaScript via C++
description: "Get info about Product."
type: docs
url: /javascript-cpp/misc/asposepdfabout/
---

_Get info about Product._

```js
function AsposePdfAbout()
```

**Return**: 

JSON object 

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **product** - Product name
* **family** - Product family
* **version** - Product version
* **releasedate** - Date release
* **producer** - Full name/producer


**Example**:

```js
  var onAsposePdfAbout = function () {
    /*Get info about Product*/
    const json = AsposePdfAbout();
    if (json.errorCode == 0) document.getElementById('output').textContent = "JSON:\n" + JSON.stringify(json, null, 4);
    else document.getElementById('output').textContent = json.errorText;
  }

```
**Web Worker**:
```js
  /*Create Web Worker*/
  const AsposePDFWebWorker = new Worker("AsposePDFforJS.js");
  AsposePDFWebWorker.onerror = evt => console.log(`Error from Web Worker: ${evt.message}`);
  AsposePDFWebWorker.onmessage = evt => document.getElementById('output').textContent = 
    (evt.data == 'ready') ? 'loaded!' :
      (evt.data.json.errorCode == 0) ? evt.data.json.producer : `Error: ${evt.data.json.errorText}`; 

  /*Event handler*/
  const onAsposePdfAbout = e => {
    /*Get info about Product - Ask Web Worker*/
    AsposePDFWebWorker.postMessage({ "operation": 'AsposePdfAbout', "params": [] }, []);
  };
```