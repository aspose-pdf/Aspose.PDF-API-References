---
title: "AsposePdfEncrypt"
second_title: "Aspose.PDF لـ Node.js عبر C++"
description: "تشفير ملف PDF."
type: docs
url: /ar/nodejs-cpp/security/asposepdfencrypt/
---

_شفّر ملف PDF._

```js
function AsposePdfEncrypt(
    fileName,
    passwordUser,
    passwordOwner,
    permissions,
    cryptoAlgorithm,
    fileNameResult 
)
```

**Parameters**: 

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

كائن JSON

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Encrypt a PDF-file with passwords "user" and "owner", and save the "ResultEncrypt.pdf"*/
    const json = AsposePdfModule.AsposePdfEncrypt(pdf_file, "user", "owner", AsposePdfModule.Permissions.PrintDocument, AsposePdfModule.CryptoAlgorithm.RC4x40, "ResultEncrypt.pdf");
    console.log("AsposePdfEncrypt => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Encrypt a PDF-file with passwords "user" and "owner", and save the "ResultEncrypt.pdf"*/
const json = AsposePdfModule.AsposePdfEncrypt(pdf_file, "user", "owner", AsposePdfModule.Permissions.PrintDocument, AsposePdfModule.CryptoAlgorithm.RC4x40, "ResultEncrypt.pdf");
console.log("AsposePdfEncrypt => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```