---
title: "AsposePdfReplaceTextEx"
second_title: "C++를 통해 Node.js용 Aspose.PDF"
description: "정렬 제어와 함께 PDF 파일의 여러 텍스트 조각을 교체합니다."
type: docs
url: /ko/nodejs-cpp/organize/asposepdfreplacetextex/
---

_정렬 제어와 함께 PDF 파일의 여러 텍스트 조각을 교체합니다._

```js
function AsposePdfReplaceTextEx(
    fileName,
    findReplaceSpec,
    options,
    fileNameResult
)
```

**Parameters**: 

* **fileName** file name 
* **findReplaceSpec** Array, replacement specification:
  * Array of objects describing replacements:
    ```js
    [
      { findText: "text1", replaceText: "value1" },
      { findText: "text2", replaceText: "value2" }
    ]
    ```
  * Each object must contain `findText` and `replaceText` string properties
* **options** object, settings for text replacement:
  * `alignment` (string), text alignment (e.g., "left", "right", "auto")
    * When `"auto"` is used, text direction is detected automatically.
접두사 `replaceText`를 사용하여 방향을 명시적으로 강제할 수도 있습니다.
특수 유니코드 문자와 함께:
`\u200F` (RTL) 또는 `\u200E` (LTR), 가능한 경우 첫 번째 문자로 사용합니다.
  * `numPages` (string|number|Array), target pages to process:
    * number, page number as 2
    * string, include page numbers with intervals as "7, 20, 22, 30-32, 33, 36-40, 46"
    * Array, array of page numbers, such as [1,3]
  * empty object `{}` for default behavior
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
    const findReplaceSpec = [
            {
            findText: 'Aspose',
            replaceText: 'ASPOSE'
            },
            {
            findText: 'Node',
            replaceText: 'NODE'
            },
            {
            findText: 'ECMAScript',
            replaceText: '\u200FScript'
            }
    ];
    const optionsText = {numPages: 1, alignment: "auto"};
    /*Replace multiple text fragments in a PDF-file with alignment control and save the "ResultPdfReplaceTextEx.pdf"*/
    const json = AsposePdfModule.AsposePdfReplaceTextEx(pdf_file, findReplaceSpec, optionsText, "ResultPdfReplaceTextEx.pdf");
    console.log("AsposePdfReplaceTextEx => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
const findReplaceSpec = [
            {
            findText: 'Aspose',
            replaceText: 'ASPOSE'
            },
            {
            findText: 'Node',
            replaceText: 'NODE'
            },
            {
            findText: 'ECMAScript',
            replaceText: '\u200FScript'
            }
];
const optionsText = {numPages: 1, alignment: "auto"};
/*Replace multiple text fragments in a PDF-file with alignment control and save the "ResultPdfReplaceTextEx.pdf"*/
const json = AsposePdfModule.AsposePdfReplaceTextEx(pdf_file, findReplaceSpec, optionsText, "ResultPdfReplaceTextEx.pdf");
console.log("AsposePdfReplaceTextEx => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```