---
title: "AsposePdfSignPKCS7"
second_title: Aspose.PDF for JavaScript via C++
description: "Sign a PDF-file with digital signatures."
type: docs
url: /javascript-cpp/security/asposepdfsignpkcs7/
---

_Sign a PDF-file with digital signatures._

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
        `Result:\n${(evt.data.operation == 'AsposePdfPrepare') ?
          'file prepared!':
          DownloadFile(evt.data.json.fileNameResult, "application/pdf", evt.data.params[0])}` :
        `Error: ${evt.data.json.errorText}`;

  /*Set the default PKCS7 key filename*/
  var fileSign = "test.pfx";
  /*Set the default image (Signature Appearance) filename: 'Aspose.jpg' already loaded, see settings in 'settings.json'*/
  var signatureAppearance = "Aspose.jpg";

  /*Event handler*/
  const ffileSignPKCS7 = e => {
    const file_reader = new FileReader();
    file_reader.onload = event => {
      const pageNum = 1;
      const pswSign = document.getElementById("passwordSign").value;
      const setXIndent = 100;
      const setYIndent = 100;
      const setHeight = 200;
      const setWidth = 100;
      const reason = 'Reason';
      const contact = 'contact@test.com';
      const location = 'Location';
      const isVisible = 1;
      /*Sign a PDF-file with digital signatures and save the "ResultSignPKCS7.pdf" - Ask Web Worker*/
      AsposePDFWebWorker.postMessage(
        { "operation": 'AsposePdfSignPKCS7',
          "params": [event.target.result, e.target.files[0].name, pageNum, fileSign, pswSign, setXIndent, setYIndent,
                     setHeight, setWidth, reason, contact, location, isVisible, signatureAppearance, "ResultSignPKCS7.pdf"] },
        [event.target.result]
      );
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };

  const ffileSign = e => {
    const file_reader = new FileReader();
    /*Set the PKCS7 key filename*/
    fileSign = e.target.files[0].name;
    file_reader.onload = event => {
      /*Save the BLOB in the Memory FS for processing*/
      AsposePDFWebWorker.postMessage(
        { "operation": 'AsposePdfPrepare', "params": [event.target.result, fileSign] },
        [event.target.result]
      );
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };

  const ffileImage = e => {
    const file_reader = new FileReader();
    /*Set the image filename*/
    signatureAppearance = e.target.files[0].name;
    file_reader.onload = event => {
      /*Save the BLOB in the Memory FS for processing*/
      AsposePDFWebWorker.postMessage(
        { "operation": 'AsposePdfPrepare', "params": [event.target.result, signatureAppearance] },
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
  /*Set the default PKCS7 key filename*/
  var fileSign = "/test.pfx";

  var ffileSign = function (e) {
    const file_reader = new FileReader();
    /*Set the PKCS7 key filename*/
    fileImage = e.target.files[0].name;
    file_reader.onload = (event) => {
      /*Save the BLOB in the Memory FS for processing*/
      AsposePdfPrepare(event.target.result, fileSign);
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };

  /*Set the default image (Signature Appearance) filename*/
  var signatureAppearance = "/Aspose.jpg";

  var ffileImage = function (e) {
    const file_reader = new FileReader();
    /*Set the image filename*/
    signatureAppearance = e.target.files[0].name;
    file_reader.onload = (event) => {
      /*Save the BLOB in the Memory FS for processing*/
      AsposePdfPrepare(event.target.result, signatureAppearance);
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };

  var ffileSignPKCS7 = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      let pswSign = document.getElementById("passwordSign").value;
      /*Sign a PDF-file with digital signatures and save the "ResultSignPKCS7.pdf"*/
      const json = AsposePdfSignPKCS7(event.target.result, e.target.files[0].name, 1, fileSign, pswSign, 200, 200, 200, 100, "TEST", "test@test.com", "EU", 1, signatureAppearance,"ResultSignPKCS7.pdf");
      if (json.errorCode == 0) document.getElementById('output').textContent = json.fileNameResult
      else document.getElementById('output').textContent = json.errorText;
      /*Make a link to download the result file*/
      DownloadFile(json.fileNameResult, "application/pdf");
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```
