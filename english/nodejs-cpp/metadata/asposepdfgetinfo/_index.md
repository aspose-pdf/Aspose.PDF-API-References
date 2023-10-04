---
title: "AsposePdfGetInfo"
second_title: Aspose.PDF for Node.js via C++
description: "Get info (metadata) from a PDF-file."
type: docs
url: /nodejs-cpp/metadata/asposepdfgetinfo/
---

_Get info (metadata) from a PDF-file._

```js
function AsposePdfGetInfo(
    fileName
)
```

**Parameters**: 

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
* **permission** - PDF permission
* **size** - PDF page size
* **pagecount** - Page count


**CommonJS**:

```js
const AsposePdf = require('.//AsposePDFforNode.cjs');
const pdf_file = 'ReadMe.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Get info (metadata) from a PDF-file*/
    const json = AsposePdfModule.AsposePdfGetInfo(pdf_file);
    /* JSON
     Title:    json.title
     Creator:  json.creator
     Author:   json.author 
     Subject:  json.subject
     Keywords: json.keywords
     Creation Date: json.creation
     Modify Date:   json.mod
     PDF format: json.format
     PDF version: json.version
     PDF is PDF/A: json.ispdfa
     PDF is PDF/UA: json.ispdfua
     PDF permission: json.permission
     PDF page size: json.size
     Page count: json.pagecount
    */
    console.log("AsposePdfGetInfo => %O", json.errorCode == 0 ? 'Title: ' + json.title : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from './/AsposePDFforNode.mjs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'ReadMe.pdf';
/*Get info (metadata) from a PDF-file*/
const json = AsposePdfModule.AsposePdfGetInfo(pdf_file);
/* JSON
 Title:    json.title
 Creator:  json.creator
 Author:   json.author 
 Subject:  json.subject
 Keywords: json.keywords
 Creation Date: json.creation
 Modify Date:   json.mod
 PDF format: json.format
 PDF version: json.version
 PDF is PDF/A: json.ispdfa
 PDF is PDF/UA: json.ispdfua
 PDF permission: json.permission
 PDF page size: json.size
 Page count: json.pagecount
*/
console.log("AsposePdfGetInfo => %O", json.errorCode == 0 ? 'Title: ' + json.title : json.errorText);
```