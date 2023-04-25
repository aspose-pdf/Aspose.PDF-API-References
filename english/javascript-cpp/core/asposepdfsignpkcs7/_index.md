---
title: "AsposePdfSignPKCS7"
second_title: Aspose.PDF for JavaScript via C++
description: "Sign PDF with digital signatures."
type: docs
url: /javascript-cpp/core/asposepdfsignpkcs7/
---

_Sign PDF with digital signatures._

```js
function AsposePdfSignPKCS7(
    fileBlob,
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

* **fileBlob** Blob object
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
* **fileResultName** result file name 

**Return**:

JSON object

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **fileNameResult** - result file name

**Example**:

```js
  /*set the default PKCS7 key filename*/
  var fileSign = "/test.pfx";

  var ffileSign = function (e) {
    const file_reader = new FileReader();
    /*set the PKCS7 key filename*/
    fileImage = e.target.files[0].name;
    file_reader.onload = (event) => {
      /*prepare(save) the PKCS7 key file from BLOB*/
      AsposePdfPrepare(event.target.result, fileSign);
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };

  /*set the default image (Signature Appearance) filename*/
  var signatureAppearance = "/Aspose.jpg";

  var ffileImage = function (e) {
    const file_reader = new FileReader();
    /*set the image filename*/
    signatureAppearance = e.target.files[0].name;
    file_reader.onload = (event) => {
      /*prepare(save) the image file from BLOB*/
      AsposePdfPrepare(event.target.result, signatureAppearance);
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };

  var ffileSignPKCS7 = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      let pswSign = document.getElementById("passwordSign").value;
      /*sign a PDF-file and save the "ResultSignPKCS7.pdf"*/
      const json = AsposePdfSignPKCS7(event.target.result, e.target.files[0].name, 1, fileSign, pswSign, 200, 200, 200, 100, "TEST", "test@test.com", "EU", 1, signatureAppearance,"ResultSignPKCS7.pdf");
      if (json.errorCode == 0) document.getElementById('output').textContent = json.fileNameResult;
      else document.getElementById('output').textContent = json.errorText;
      /*make a link to download the result file*/
      DownloadFile(json.fileNameResult, "application/pdf");
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```
