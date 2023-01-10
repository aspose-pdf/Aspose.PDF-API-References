---
title: "AsposePdfEncrypt"
second_title: Aspose.PDF for JavaScript via C++
description:  "Encrypt PDF file."
type: docs
url: /javascript-cpp/core/asposepdfencrypt/
---

_Encrypt PDF file._

```js
function AsposePdfEncrypt(
    fileBlob ,
    fileName ,
    passwordUser ,
    passwordOwner ,
    permissions ,
    cryptoAlgorithm ,
    fileResultName 
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
* **fileResultName** result file name 

**Return**:

JSON object 

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **fileNameResult** - result file name



**Example**:

```js
  var ffileEncrypt = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*encrypt a PDF-file with passwords "user" and "owner", and save the "ResultDecrypt.pdf"*/
      const json = AsposePdfEncrypt(event.target.result, e.target.files[0].name, "user", "owner", Module.Permissions.PrintDocument, Module.CryptoAlgorithm.RC4x40, "ResultEncrypt.pdf");
      if (json.errorCode == 0) document.getElementById('output').textContent = json.fileNameResult;
      else document.getElementById('output').textContent = json.errorText;
      /*make a link to download the result file*/
      DownloadFile(json.fileNameResult, "application/pdf");
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```
