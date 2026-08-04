---
title: "AsposePdfSignPKCS7"
second_title: "C++를 통해 Node.js용 Aspose.PDF"
description: "PDF 파일에 디지털 서명을 추가합니다."
type: docs
url: /ko/nodejs-cpp/security/asposepdfsignpkcs7/
---

_PDF 파일에 디지털 서명을 사용하여 서명합니다._

```js
function AsposePdfSignPKCS7(
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

JSON 객체

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Key PKCS7*/
    const test_pfx_file = 'test.pfx';
    /*Signature appearance*/
    const sign_img_file = 'Aspose.jpg';
    /*Sign a PDF-file with digital signatures and save the "ResultSignPKCS7.pdf"*/
    const json = AsposePdfModule.AsposePdfSignPKCS7(pdf_file, 1, test_pfx_file, "Pa$$w0rd2023", 100, 100, 200, 100, "Reason", "Contact", "Location", 1, sign_img_file, "ResultSignPKCS7.pdf");
    console.log("AsposePdfSignPKCS7 => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Key PKCS7*/
const test_pfx_file = 'test.pfx';
/*Signature appearance*/
const sign_img_file = 'Aspose.jpg';
/*Sign a PDF-file with digital signatures and save the "ResultSignPKCS7.pdf"*/
const json = AsposePdfModule.AsposePdfSignPKCS7(pdf_file, 1, test_pfx_file, "Pa$$w0rd2023", 100, 100, 200, 100, "Reason", "Contact", "Location", 1, sign_img_file, "ResultSignPKCS7.pdf");
console.log("AsposePdfSignPKCS7 => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```