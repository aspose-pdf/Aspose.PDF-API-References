---
title: "AsposePdfChangePassword"
second_title: Aspose.PDF for JavaScript via C++
description:  "Change passwords of the PDF-file."
type: docs
url: /javascript-cpp/security/asposepdfchangepassword/
---

_Change passwords of the PDF-file._

```js
function AsposePdfChangePassword(
    fileBlob,
    fileName,
    ownerPassword,
    newUserPassword,
    newOwnerPassword,
    fileNameResult 
)
```

**Parameters**: 

* **fileBlob** Blob object 
* **fileName** file name 
* **ownerPassword** owner password
* **newUserPassword** new user password
* **newOwnerPassword** new owner password
* **fileNameResult** result file name 

**Return**:

JSON object 

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **fileNameResult** - result file name



**Example**:

```js
  var ffilePdfChangePassword = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*Change passwords of the PDF file from "owner" to "newowner" and save the "ResultPdfChangePassword.pdf"*/
      const json = AsposePdfChangePassword(event.target.result, e.target.files[0].name, "owner", "newuser", "newowner", "ResultPdfChangePassword.pdf");
      if (json.errorCode == 0) document.getElementById('output').textContent = json.fileNameResult;
      else document.getElementById('output').textContent = json.errorText;
      /*Make a link to download the result file*/
      DownloadFile(json.fileNameResult, "application/pdf");
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```
**Web Worker**:
```js
  /*Create Web Worker*/
  const AsposePDFWebWorker = new Worker("AsposePDFforJS.js");
  AsposePDFWebWorker.onerror = evt => console.log(`Error from Web Worker: ${evt.message}`);
  AsposePDFWebWorker.onmessage = evt => document.getElementById('output').textContent = 
    (evt.data == 'ready') ? 'loaded!' :
      (evt.data.json.errorCode == 0) ?
        `Result:\n${DownloadFile(evt.data.json.fileNameResult, "application/pdf", evt.data.params[0])}` :
        `Error: ${evt.data.json.errorText}`;

  /*Event handler*/
  const ffilePdfChangePassword = e => {
    const file_reader = new FileReader();
    file_reader.onload = event => {
      const ownerPassword = 'owner'; /*Owner password*/
      const newUserPassword = "newuser"; /*New user password*/
      const newOwnerPassword = "newowner"; /*New owner password*/
      /*Change passwords of the PDF file from "owner" to "newowner" and save the "ResultPdfChangePassword.pdf" - Ask Web Worker*/
      AsposePDFWebWorker.postMessage(
        { "operation": 'AsposePdfChangePassword',
          "params": [event.target.result, e.target.files[0].name, ownerPassword, newUserPassword, newOwnerPassword,
                     "ResultPdfChangePassword.pdf"] },
        [event.target.result]
      );
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };

  /*Make a link to download the result file*/
  const DownloadFile = (filename, mime, content) => {
      mime = mime || "application/octet-stream";
      var link = document.createElement("a"); 
      link.href = URL.createObjectURL(new Blob([content], {type: mime}));
      link.download = filename;
      link.innerHTML = "Click here to download the file " + filename;
      document.body.appendChild(link); 
      document.body.appendChild(document.createElement("br"));
      return filename;
    }
```