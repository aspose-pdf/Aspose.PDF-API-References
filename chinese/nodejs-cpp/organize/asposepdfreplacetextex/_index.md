---
title: "AsposePdfReplaceTextEx"
second_title: "Aspose.PDF 用于 Node.js via C++"
description: "在 PDF 文件中替换多个文本片段并进行对齐控制。"
type: docs
url: /zh/nodejs-cpp/organize/asposepdfreplacetextex/
---

_在 PDF 文件中替换多个文本片段，并可控制对齐._

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
也可以通过在 `replaceText` 前加前缀显式强制方向
使用特殊的 Unicode 字符：
`\\u200F` (RTL) 或 `\\u200E` (LTR)，最好作为第一个字符
  * `numPages` (string|number|Array), target pages to process:
    * number, page number as 2
    * string, include page numbers with intervals as "7, 20, 22, 30-32, 33, 36-40, 46"
    * Array, array of page numbers, such as [1,3]
  * empty object `{}` for default behavior
* **fileNameResult** result file name 

**Return**: 

JSON 对象

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