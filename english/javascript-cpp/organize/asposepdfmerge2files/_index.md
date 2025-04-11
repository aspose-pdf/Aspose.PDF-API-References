---
title: "AsposePdfMerge2Files"
second_title: Aspose.PDF for JavaScript via C++
description:  "Merge two PDF-files."
type: docs
url: /javascript-cpp/organize/asposepdfmerge2files/
---

_Merge two PDF-files._

```js
function AsposePdfMerge2Files(
    fileBlob1,
    fileBlob2,
    fileName1,
    fileName2,
    fileNameResult 
)
```

**Parameters**: 
  * **fileBlob1** Blob object #1 
  * **fileBlob2** Blob object #2 
  * **fileName1** file name #1 
  * **fileName2** file name #2 
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
                    fileProcess('AsposePdfMerge2Files', evt.data.json.optdata[0].file, {"fileName2": evt.data.json.fileNameResult}) ?? 'wait please...' : 
                    DownloadFile(evt.data.json.fileNameResult, "application/pdf", evt.data.params[0]) /*AsposePdfMerge2Files*/
                   }` :
        `Error: ${evt.data.json.errorText}`;

  /*Event handler. Only two files are merged. If only one file is selected, then use it. For the second file you need to perform AsposePdfPrepare */
  const ffileMerge = evt => fileProcess('AsposePdfPrepare',  evt.target.files[(evt.target.files.length == 1) ? 0 : 1],
                                        [{"operation": 'AsposePdfMerge2Files', "file": evt.target.files[0]}])
  /* Ask Web Worker */
  const fileProcess = (operation, ffile, optdata) => {
    const file_reader = new FileReader();
    file_reader.onload = event => {
      if (operation == 'AsposePdfPrepare')
        return AsposePDFWebWorker.postMessage(
                 { "operation": operation, "params": [event.target.result, ffile.name, optdata] },
                 [event.target.result]
               );
      else if (operation == 'AsposePdfMerge2Files')
        return AsposePDFWebWorker.postMessage(
                 { "operation": operation, 
                   "params": [event.target.result, undefined, ffile.name, (optdata === undefined) ? ffile.name : optdata.fileName2,
                              `Result${operation}.pdf`] },
                 [event.target.result]
               );
    }
    file_reader.readAsArrayBuffer(ffile);
  }

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
  var ffileMerge = function (e) {
    const file_reader = new FileReader();
    function readFile(index) {
      /*Only two files*/
      if (index >= e.target.files.length || index >= 2) {
        /*Merge two PDF-files and save the "ResultMerge.pdf"*/
        const json = AsposePdfMerge2Files(undefined, undefined, e.target.files[0].name, e.target.files[1].name, "ResultMerge.pdf");
        if (json.errorCode == 0) document.getElementById('output').textContent = json.fileNameResult
        else document.getElementById('output').textContent = json.errorText;
        /*Make a link to download the result file*/
        DownloadFile(json.fileNameResult, "application/pdf");
        return;
      }
      const file = e.target.files[index];
      file_reader.onload = function (event) {
        /*Save the BLOB in the Memory FS for processing*/
        AsposePdfPrepare(event.target.result, file.name);
        readFile(index + 1)
      }
      file_reader.readAsArrayBuffer(file);
    }
    readFile(0);
  }
```
