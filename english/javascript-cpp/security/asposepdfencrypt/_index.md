---
title: "AsposePdfEncrypt"
second_title: Aspose.PDF for JavaScript via C++
description:  "Encrypt a PDF-file."
type: docs
url: /javascript-cpp/security/asposepdfencrypt/
---

_Encrypt a PDF-file._

```js
function AsposePdfEncrypt(
    fileBlob,
    fileName,
    passwordUser,
    passwordOwner,
    permissions,
    cryptoAlgorithm,
    fileNameResult 
)
```

**Parameters**: 

* **fileBlob** Blob object 
* **fileName** file name 
* **passwordUser** user password 
* **passwordOwner** owner password 
* **permissions** encrypt permissions:
  * Module.Permissions.PrintDocument
  * Module.Permissions.ModifyContent
  * Module.Permissions.ExtractContent
  * Module.Permissions.ModifyTextAnnotations
  * Module.Permissions.FillForm
  * Module.Permissions.ExtractContentWithDisabilities
  * Module.Permissions.AssembleDocument
  * Module.Permissions.PrintingQuality 
* **cryptoAlgorithm** encrypt algorithm:
  * Module.CryptoAlgorithm.RC4x40
  * Module.CryptoAlgorithm.RC4x128
  * Module.CryptoAlgorithm.AESx128
  * Module.CryptoAlgorithm.AESx256 
* **fileNameResult** result file name 

**Return**:

JSON object 

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **fileNameResult** - result file name


**Web Worker example**:
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
  const ffileEncrypt = e => {
    const file_reader = new FileReader();
    file_reader.onload = event => {
      const password_user = 'user';
      const password_owner = 'owner';
      const permissions = 'Module.Permissions.PrintDocument';
      const algorithm = 'Module.CryptoAlgorithm.RC4x40';
      /*Encrypt a PDF-file with passwords "user" and "owner", and save the "ResultEncrypt.pdf" - Ask Web Worker*/
      AsposePDFWebWorker.postMessage(
        { "operation": 'AsposePdfEncrypt',
          "params": [event.target.result, e.target.files[0].name, password_user, password_owner,
                     permissions, algorithm, "ResultEncrypt.pdf"] },
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
**Simple example**:
```js
  var ffileEncrypt = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*Encrypt a PDF-file with passwords "user" and "owner", and save the "ResultDecrypt.pdf"*/
      const json = AsposePdfEncrypt(event.target.result, e.target.files[0].name, "user", "owner", Module.Permissions.PrintDocument, Module.CryptoAlgorithm.RC4x40, "ResultEncrypt.pdf");
      if (json.errorCode == 0) document.getElementById('output').textContent = json.fileNameResult;
      else document.getElementById('output').textContent = json.errorText;
      /*Make a link to download the result file*/
      DownloadFile(json.fileNameResult, "application/pdf");
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```
