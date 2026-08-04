---
title: "AsposePdfGetWordsCharactersCount"
second_title: "Aspose.PDF untuk Node.js via C++"
description: "Dapatkan jumlah kata dan karakter dalam file PDF."
type: docs
url: /id/nodejs-cpp/metadata/asposepdfgetwordscharacterscount/
---

_Dapatkan jumlah kata dan karakter dalam file PDF._

```js
function AsposePdfGetWordsCharactersCount(
    fileName
)
```

**Parameters**: 

* **fileName** file name 

**Return**: 

Objek JSON

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **words** - words count
* **characters** - characters count


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Get words and characters count in a PDF-file*/
    const json = AsposePdfModule.AsposePdfGetWordsCharactersCount(pdf_file);
    /* JSON
       Words count      : json.words
       Characters count : json.characters
    */
    console.log("AsposePdfGetWordsCharactersCount => %O", json.errorCode == 0 ? 'Words count: ' + json.words : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Get words and characters count in a PDF-file*/
const json = AsposePdfModule.AsposePdfGetWordsCharactersCount(pdf_file);
/* JSON
   Words count      : json.words
   Characters count : json.characters
*/
console.log("AsposePdfGetWordsCharactersCount => %O", json.errorCode == 0 ? 'Words count: ' + json.words : json.errorText);
```