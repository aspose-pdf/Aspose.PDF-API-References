---
title: "AsposePdfGetInfo"
second_title: Aspose.PDF for JavaScript via C++
description: "Get info (metadata) from a PDF-file."
type: docs
url: /javascript-cpp/metadata/asposepdfgetinfo/
---

_Get info (metadata) from a PDF-file._

```js
function AsposePdfGetInfo(
    fileBlob,
    fileName
)
```

**Parameters**: 

* **fileBlob** Blob object 
* **fileName** file name 

**Return**: 

JSON object 

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **title** - title
* **creator** - creator
* **author** - author
* **subject** - subject
* **keywords** - keywords
* **creation** - creation date
* **mod** - modify date
* **format** - PDF format
* **version** - PDF version
* **ispdfa** - PDF is PDF/A
* **ispdfua** - PDF is PDF/UA
* **islinearized** - PDF is linearized
* **isencrypted** - PDF is encrypted
* **permission** - PDF permission
* **size** - PDF page size
* **pagecount** - Page count
* **annotationcount** - Annotation count
* **bookmarkcount** - Bookmark count
* **attachmentcount** - Attachment count
* **metadatacount** - Metadata count
* **javascriptcount** - JavaScript count
* **imagecount** - Image count
* **tablecount** - Table count


**Web Worker example**:
```js
  /*Create Web Worker*/
  const AsposePDFWebWorker = new Worker("AsposePDFforJS.js");
  AsposePDFWebWorker.onerror = (evt) =>
  console.log(`Error from Web Worker: ${evt.message}`);
AsposePDFWebWorker.onmessage = (evt) =>
  (document.getElementById("output").textContent =
    evt.data == "ready"
      ? "loaded!"
      : evt.data.json.errorCode == 0
      ? `info:\n${JSON.stringify(evt.data.json, null, 4)}`
      : `Error: ${evt.data.json.errorText}`);
evt.data.json.errorCode !== 0
  ? `Error: ${evt.data.json.errorText}`
  : "Title               : " + evt.data.json.title +
    "\nCreator           : " + evt.data.json.creator +
    "\nAuthor            : " + evt.data.json.author +
    "\nSubject           : " + evt.data.json.subject +
    "\nKeywords          : " + evt.data.json.keywords +
    "\nCreation Date     : " + evt.data.json.creation +
    "\nModify Date       : " + evt.data.json.mod +
    "\nPDF format        : " + evt.data.json.format +
    "\nPDF version       : " + evt.data.json.version +
    "\nPDF is PDF/A      : " + evt.data.json.ispdfa +
    "\nPDF is PDF/UA     : " + evt.data.json.ispdfua +
    "\nPDF is linearized : " + evt.data.json.islinearized +
    "\nPDF is encrypted  : " + evt.data.json.encrypted +
    "\nPDF permission    : " + evt.data.json.permission +
    "\nPDF page size     : " + evt.data.json.size +
    "\nPage count        : " + evt.data.json.pagecount +
    "\nAnnotation count  : " + evt.data.json.annotationcount +
    "\nBookmark count    : " + evt.data.json.bookmarkcount +
    "\nAttachment count  : " + evt.data.json.attachmentcount +
    "\nMetadata count    : " + evt.data.json.metadatacount +
    "\nJavaScript count  : " + evt.data.json.javascriptcount +
    "\nImage count       : " + evt.data.json.imagecount +
    "\nTable count       : " + evt.data.json.tablecount;

  /*Event handler*/
  const ffilePdfGetInfo = e => {
    const file_reader = new FileReader();
    file_reader.onload = event => {
      /*Get info (metadata) from a PDF-file - Ask Web Worker*/
      AsposePDFWebWorker.postMessage({ "operation": 'AsposePdfGetInfo', "params": [event.target.result, e.target.files[0].name] }, [event.target.result]);
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```
**Simple example**:
```js
  var ffilePdfGetInfo = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*Get info (metadata) from a PDF-file*/
      const json = AsposePdfGetInfo(event.target.result, e.target.files[0].name);
      /* JSON
       Title             : json.title
       Creator           : json.creator
       Author            : json.author
       Subject           : json.subject
       Keywords          : json.keywords
       Creation Date     : json.creation
       Modify Date       : json.mod
       PDF format        : json.format
       PDF version       : json.version
       PDF is PDF/A      : json.ispdfa
       PDF is PDF/UA     : json.ispdfua
       PDF is linearized : json.islinearized
       PDF is encrypted  : json.isencrypted
       PDF permission    : json.permission
       PDF page size     : json.size
       Page count        : json.pagecount
       Annotation count  : json.annotationcount
       Bookmark count    : json.bookmarkcount
       Attachment count  : json.attachmentcount
       Metadata count    : json.metadatacount
       JavaScript count  : json.javascriptcount
       Image count       : json.imagecount
       Table count       : json.tablecount
      */
      if (json.errorCode == 0) document.getElementById('output').textContent = 
          "Title               : " + json.title
        + "\nCreator           : " + json.creator
        + "\nAuthor            : " + json.author
        + "\nSubject           : " + json.subject
        + "\nKeywords          : " + json.keywords
        + "\nCreation Date     : " + json.creation
        + "\nModify Date       : " + json.mod
        + "\nPDF format        : " + json.format
        + "\nPDF version       : " + json.version
        + "\nPDF is PDF/A      : " + json.ispdfa
        + "\nPDF is PDF/UA     : " + json.ispdfua
        + "\nPDF is linearized : " + json.islinearized
        + "\nPDF is encrypted  : " + json.isencrypted
        + "\nPDF permission    : " + json.permission
        + "\nPDF page size     : " + json.size
        + "\nPage count        : " + json.pagecount
        + "\nAnnotation count  : " + json.annotationcount
        + "\nBookmark count    : " + json.bookmarkcount
        + "\nAttachment count  : " + json.attachmentcount
        + "\nMetadata count    : " + json.metadatacount
        + "\nJavaScript count  : " + json.javascriptcount
        + "\nImage count       : " + json.imagecount
        + "\nTable count       : " + json.tablecount
      else document.getElementById('output').textContent = json.errorText;
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```
