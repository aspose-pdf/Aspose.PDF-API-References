---
title: "AsposePdfTablesToCSV"
second_title: Aspose.PDF for JavaScript via C++
description:  "Convert a PDF-file to CSV (extract tables)."
type: docs
url: /javascript-cpp/convert/asposepdftablestocsv/
---

_Convert a PDF-file to CSV (extract tables)._

```
function AsposePdfTablesToCSV(
    fileBlob,
    fileName,
    fileNameResult,
    delimiter
)
```

**Parameters**: 
  * **fileBlob** Blob object 
  * **fileName** file name 
  * **fileNameResult** result file name template (for sample: "ResultPdfTablesToCSV{0:D2}.csv" where {0}, {0:D2}, {0:D3}, {0:Dn} - format page number) 
  * **delimiter** delimiter for csv (comma-separated value), default ";"

**Return**: 
JSON object 
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **filesCount** - csv files count
  * **filesNameResult** - array of result filenames



**Example**:
```js
  var ffileToCSV = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*Convert a PDF-file to CSV (extract tables) with template "ResultPdfTablesToCSV{0:D2}.csv" ({0}, {0:D2}, {0:D3}, ... format page number), TAB as delimiter*/
      const json = AsposePdfTablesToCSV(event.target.result, e.target.files[0].name, "ResultPdfTablesToCSV{0:D2}.csv", "\t");
      if (json.errorCode == 0) {
        document.getElementById('output').textContent = "Files(tables) count: " + json.filesCount.toString();
        /*Make links to result files*/
        for (let fileIndex = 0; fileIndex < json.filesCount; fileIndex++) DownloadFile(json.filesNameResult[fileIndex], "text/csv");
      }
      else document.getElementById('output').textContent = json.errorText;
    };
    file_reader.readAsArrayBuffer(e.target.files[0]);
  };
```
**Web Worker**:
```js
  /*Create Web Worker*/
  const AsposePDFWebWorker = new Worker("AsposePDFforJS.js");
  AsposePDFWebWorker.onerror = evt => console.log(`Error from Web Worker: ${evt.message}`);
  AsposePDFWebWorker.onmessage = evt => document.getElementById('output').textContent = 
    (evt.data == 'ready') ? 'loaded!' :
      (evt.data.json.errorCode == 0) ? 
        `Files(tables) count: ${evt.data.json.filesCount.toString()}\n${evt.data.params.forEach(
          (element, index) => DownloadFile(evt.data.json.filesNameResult[index], "text/csv", element) ) ?? ""}` : 
        `Error: ${evt.data.json.errorText}`;

  /*Event handler*/
  const ffileToCSV = e => {
    const file_reader = new FileReader();
    file_reader.onload = event => {
      /*Convert a PDF-file to CSV (extract tables) with template "ResultPdfTablesToCSV{0:D2}.csv" ({0}, {0:D2}, {0:D3}, ... format page number), TAB as delimiter and save - Ask Web Worker*/
      AsposePDFWebWorker.postMessage({ "operation": 'AsposePdfTablesToCSV', "params": [event.target.result, e.target.files[0].name, "ResultPdfTablesToCSV{0:D2}.csv", "\t"] }, [event.target.result]);
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