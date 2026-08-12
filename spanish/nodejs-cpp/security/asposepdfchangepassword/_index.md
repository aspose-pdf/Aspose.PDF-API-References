---
title: "AsposePdfChangePassword"
second_title: "Aspose.PDF para Node.js via C++"
description: "Cambie las contraseñas del archivo PDF."
type: docs
url: /es/nodejs-cpp/security/asposepdfchangepassword/
---

_Cambiar contraseñas del archivo PDF._

```js
function AsposePdfChangePassword(
    fileName,
    ownerPassword,
    newUserPassword,
    newOwnerPassword,
    fileNameResult 
)
```

**Parameters**: 

* **fileName** file name 
* **ownerPassword** owner password
* **newUserPassword** new user password
* **newOwnerPassword** new owner password
* **fileNameResult** result file name 

**Return**:

Objeto JSON

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_encrypt_file = 'ResultEncrypt.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Change passwords of the PDF-file from "owner" to "newowner" and save the "ResultPdfChangePassword.pdf"*/
    const json = AsposePdfModule.AsposePdfChangePassword(pdf_encrypt_file, "owner", "newuser", "newowner", "ResultPdfChangePassword.pdf");
    console.log("AsposePdfChangePassword => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_encrypt_file = 'ResultEncrypt.pdf';
/*Change passwords of the PDF-file from "owner" to "newowner" and save the "ResultPdfChangePassword.pdf"*/
const json = AsposePdfModule.AsposePdfChangePassword(pdf_encrypt_file, "owner", "newuser", "newowner", "ResultPdfChangePassword.pdf");
console.log("AsposePdfChangePassword => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```