---
title: "AsposePdfDecrypt"
second_title: "Aspose.PDF لـ Node.js عبر C++"
description: "فك تشفير ملف PDF."
type: docs
url: /ar/nodejs-cpp/security/asposepdfdecrypt/
---

_فك تشفير ملف PDF._

```js
function AsposePdfDecrypt(
    fileName,
    password,
    fileNameResult 
)
```

**Parameters**: 

* **fileName** file name 
* **password** user password 
* **fileNameResult** result file name 

**Return**:

كائن JSON

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_encrypt_file = 'ResultEncrypt.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Decrypt a PDF-file with password is "owner" and save the "ResultDecrypt.pdf"*/
    const json = AsposePdfModule.AsposePdfDecrypt(pdf_encrypt_file, "owner", "ResultDecrypt.pdf");
    console.log("AsposePdfDecrypt => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_encrypt_file = 'ResultEncrypt.pdf';
/*Decrypt a PDF-file with password is "owner" and save the "ResultDecrypt.pdf"*/
const json = AsposePdfModule.AsposePdfDecrypt(pdf_encrypt_file, "owner", "ResultDecrypt.pdf");
console.log("AsposePdfDecrypt => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```