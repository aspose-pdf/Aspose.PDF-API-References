---
title: "AsposePdfChangePassword"
second_title: "Aspose.PDF 用于 Node.js via C++"
description: "更改 PDF 文件的密码。"
type: docs
url: /zh/nodejs-cpp/security/asposepdfchangepassword/
---

_更改 PDF 文件的密码._

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

JSON 对象

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