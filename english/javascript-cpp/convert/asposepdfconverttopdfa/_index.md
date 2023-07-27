---
title: "AsposePdfConvertToPDFA"
second_title: Aspose.PDF for JavaScript via C++
description:  "Convert a PDF-file to PDF/A."
type: docs
url: /javascript-cpp/convert/asposepdfconverttopdfa/
---

_Convert a PDF-file to PDF/A._

```js
function AsposePdfConvertToPDFA(
    fileBlob,
    fileName,
    pdfFormat,
    fileResultName,
    fileNameLogResult
)
```

**Parameters**: 

* **fileBlob** Blob object
* **fileName** file name
* **pdfFormat** format PDF/A:
  * Module.PdfFormat.PDF_A_1A
  * Module.PdfFormat.PDF_A_1B
  * Module.PdfFormat.PDF_A_2A
  * Module.PdfFormat.PDF_A_3A
  * Module.PdfFormat.PDF_A_2U
  * Module.PdfFormat.PDF_A_3B
  * Module.PdfFormat.PDF_A_3U
* **fileResultName** result file name
* **fileNameLogResult** result Log (xml) file name

**Return**: 
JSON object 
  * **errorCode** - code error (0 no error)
  * **errorText** - text error ("" no error)
  * **fileNameResult** - result file name
  * **fileNameLogResult** - result Log (xml) file name


**Example**:
```js
var ffilePdfConvertToPDFA = function (e) {
    const file_reader = new FileReader();
    file_reader.onload = (event) => {
      /*Convert a PDF-file to PDF/A(1A) and save the "ResultConvertToPDFA.pdf"*/
      /*During conversion process, the validation is also performed, "ResultConvertToPDFA.xml"*/
      const json = AsposePdfConvertToPDFA(event.target.result, e.target.files[0].name, Module.PdfFormat.PDF_A_1A, "ResultConvertToPDFA.pdf", "ResultConvertToPDFA.xml");
      if (json.errorCode == 0)
      {
        document.getElementById('output').textContent = json.fileNameResult + "\nLog file (xml format): " + json.fileNameLogResult;
        /*Make a link to download the result file*/
        DownloadFile(json.fileNameResult, "application/pdf");
      }
      else document.getElementById('output').textContent = json.errorText + "\nLog file (xml format): " + json.fileNameLogResult;
      /*Make a link to download the Log (xml)*/
      DownloadFile(json.fileNameLogResult, "application/xml");
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
        `Result:\n${DownloadFile(evt.data.json.fileNameResult, "application/pdf", evt.data.params[0])}\n
                  ${DownloadFile(evt.data.json.fileNameLogResult, "application/xml", evt.data.params[1])}` :
        `Error: ${evt.data.json.errorText}`;

  /*Event handler*/
  const ffilePdfConvertToPDFA = e => {
    const file_reader = new FileReader();
    file_reader.onload = event => {
      const pdfFormat = 'Module.PdfFormat.PDF_A_1A';
      /*Convert a PDF-file to PDF/A(1A) and save the "ResultConvertToPDFA.pdf"*/
      /*During conversion process, the validation is also performed, "ResultConvertToPDFA.xml"- Ask Web Worker*/
      AsposePDFWebWorker.postMessage(
        { "operation": 'AsposePdfConvertToPDFA',
          "params": [event.target.result, e.target.files[0].name, pdfFormat, "ResultConvertToPDFA.pdf", "ResultConvertToPDFA.xml"] },
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