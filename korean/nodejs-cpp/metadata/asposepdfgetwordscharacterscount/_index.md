---
title: "AsposePdfGetWordsCharactersCount"
second_title: "C++를 통해 Node.js용 Aspose.PDF"
description: "PDF 파일에서 단어 및 문자 수를 가져옵니다."
type: docs
url: /ko/nodejs-cpp/metadata/asposepdfgetwordscharacterscount/
---

_PDF 파일에서 단어 및 문자 수를 가져옵니다._

```js
function AsposePdfGetWordsCharactersCount(
    fileName
)
```

**Parameters**: 

* **fileName** file name 

**Return**: 

JSON 객체

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