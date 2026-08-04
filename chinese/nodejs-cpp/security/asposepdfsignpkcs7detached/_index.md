---
title: "AsposePdfSignPKCS7Detached"
second_title: "Aspose.PDF 用于 Node.js via C++"
description: "使用分离式数字签名对 PDF 文件进行签名。"
type: docs
url: /zh/nodejs-cpp/security/asposepdfsignpkcs7detached/
---

_使用分离的数字签名对 PDF 文件进行签名._

```js
function AsposePdfSignPKCS7Detached(
    fileName,
    pageNum,
    fileSign,
    pswSign,
    setXIndent, 
    setYIndent, 
    setHeight,
    setWidth,
    reason,
    contact,
    location,
    isVisible,
    signatureAppearance,
    fileNameResult 
)
```

**Parameters**:

* **fileName** file name 
* **pageNum**  num page
* **fileSign** file Sign, PKCS#7 specification in Internet RFC 2315
* **pswSign**  password Sign
* **setXIndent** x indent
* **setYIndent** y indent
* **setHeight** height
* **setWidth** width
* **reason** reason
* **contact** contact
* **location** location
* **isVisible** visible (1 or 0)
* **signatureAppearance** image (Sign Appearance) file name 
* **fileNameResult** result file name 

**Return**:

JSON 对象

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Key PKCS7*/
    const test_pfx_file = 'sign.pfx';
    /*Signature appearance*/
    const sign_img_file = 'sign.png';
    /*Sign a PDF-file with detached digital signatures and save the "ResultSignPKCS7Detached.pdf"*/
    const json = AsposePdfModule.AsposePdfSignPKCS7Detached(pdf_file, 1, test_pfx_file, "Pa$$w0rd2023", 100, 100, 200, 100, "Reason", "Contact", "Location", 1, sign_img_file, "ResultSignPKCS7Detached.pdf");
    console.log("AsposePdfSignPKCS7Detached => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Key PKCS7*/
const test_pfx_file = 'sign.pfx';
/*Signature appearance*/
const sign_img_file = 'sign.png';
/*Sign a PDF-file with detached digital signatures and save the "ResultSignPKCS7Detached.pdf"*/
const json = AsposePdfModule.AsposePdfSignPKCS7Detached(pdf_file, 1, test_pfx_file, "Pa$$w0rd2023", 100, 100, 200, 100, "Reason", "Contact", "Location", 1, sign_img_file, "ResultSignPKCS7Detached.pdf");
console.log("AsposePdfSignPKCS7Detached => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```