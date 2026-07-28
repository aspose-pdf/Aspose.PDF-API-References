---
title: "AsposePdfAbout"
second_title: "Aspose.PDF 用于 JavaScript 通过 C++"
description: "获取有关产品的信息."
type: docs
url: /zh/javascript-cpp/misc/asposepdfabout/
---

_获取有关产品的信息。_

```js
function AsposePdfAbout()
```

**Return**: 

JSON 对象

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **product** - Product name
* **family** - Product family
* **version** - Product version
* **releasedate** - Date release
* **producer** - Full name/producer
* **islicensed** - Product is licensed


**Web Worker example**:
```js
  /*Create Web Worker*/
  const AsposePDFWebWorker = new Worker("AsposePDFforJS.js");
  AsposePDFWebWorker.onerror = evt => console.log(`Error from Web Worker: ${evt.message}`);
  AsposePDFWebWorker.onmessage = evt => document.getElementById('output').textContent = 
    (evt.data == 'ready') ? 'loaded!' :
      (evt.data.json.errorCode !== 0) ? `Error: ${evt.data.json.errorText}` :
                        "Product      : " + evt.data.json.product
                    + "\nFamily       : " + evt.data.json.family
                    + "\nVersion      : " + evt.data.json.version
                    + "\nRelease date : " + evt.data.json.releasedate
                    + "\nProducer     : " + evt.data.json.producer
                    + "\nIs licensed  : " + evt.data.json.islicensed;

  /*Event handler*/
  const onAsposePdfAbout = e => {
    /*Get info about Product - Ask Web Worker*/
    AsposePDFWebWorker.postMessage({ "operation": 'AsposePdfAbout', "params": [] }, []);
  };
```
**Simple example**:
```js
  var onAsposePdfAbout = function () {
    /*Get info about Product*/
    const json = AsposePdfAbout();
    /* JSON
    Product name       : json.product
    Product family     : json.family
    Product version    : json.version
    Date release       : json.releasedate
    Full name/producer : json.producer
    Product is licensed: json.islicensed
    */
    if (json.errorCode == 0) document.getElementById('output').textContent = "Product      : " + json.product
                                                                         + "\nFamily       : " + json.family
                                                                         + "\nVersion      : " + json.version
                                                                         + "\nRelease date : " + json.releasedate
                                                                         + "\nProducer     : " + json.producer
                                                                         + "\nIs licensed  : " + json.islicensed
    else document.getElementById('output').textContent = json.errorText;
  }
```
