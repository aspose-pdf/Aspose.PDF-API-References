---
title: "AsposePdfChangePassword"
second_title: Aspose.PDF for Node.js via C++
description:  "Change passwords of the PDF-file."
type: docs
url: /nodejs-cpp/security/asposepdfchangepassword/
---

_Change passwords of the PDF-file._

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

JSON object 

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('.//AsposePDFforNode.cjs');
const pdf_encrypt_file = 'ResultEncrypt.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Change passwords of the PDF-file from "owner" to "newowner" and save the "ResultPdfChangePassword.pdf"*/
    const json = AsposePdfModule.AsposePdfChangePassword(pdf_encrypt_file, "owner", "newuser", "newowner", "ResultPdfChangePassword.pdf");
    console.log("AsposePdfChangePassword => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from './/AsposePDFforNode.mjs';
const AsposePdfModule = await AsposePdf();
const pdf_encrypt_file = 'ResultEncrypt.pdf';
/*Change passwords of the PDF-file from "owner" to "newowner" and save the "ResultPdfChangePassword.pdf"*/
const json = AsposePdfModule.AsposePdfChangePassword(pdf_encrypt_file, "owner", "newuser", "newowner", "ResultPdfChangePassword.pdf");
console.log("AsposePdfChangePassword => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```