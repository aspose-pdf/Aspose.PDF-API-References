---
title: "AsposePdfAddTextHeaderFooter"
second_title: "Aspose.PDF pour Node.js via C++"
description: "Ajouter du texte dans l'en-tête/pied de page d'un fichier PDF."
type: docs
url: /fr/nodejs-cpp/organize/asposepdfaddtextheaderfooter/
---

_Ajouter du texte dans l'en-tête/pied de page d'un fichier PDF._

```js
function AsposePdfAddTextHeaderFooter(
    fileName,
    header, 
    footer,
    fileNameResult
)
```

**Parameters**: 

* **fileName** file name 
* **header** page header, if not need to set, use undefined or "" (empty string)
* **footer** page footer, if not need to set, use undefined or "" (empty string)
* **fileNameResult** result file name 

**Return**: 

Objet JSON

* **errorCode** - code error (0 no error)
* **errorText** - text error ("" no error)
* **fileNameResult** - result file name


**CommonJS**:

```js
const AsposePdf = require('asposepdfnodejs');
const pdf_file = 'Aspose.pdf';
AsposePdf().then(AsposePdfModule => {
    /*Add text in Header/Footer of a PDF-file and save the "ResultAddHeaderFooter.pdf"*/
    const json = AsposePdfModule.AsposePdfAddTextHeaderFooter(pdf_file, "Aspose.PDF for Node.js via C++ via C++", "ASPOSE", "ResultAddHeaderFooter.pdf");
    console.log("AsposePdfAddTextHeaderFooter => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
});
```

**ECMAScript/ES6**:

```js
import AsposePdf from 'asposepdfnodejs';
const AsposePdfModule = await AsposePdf();
const pdf_file = 'Aspose.pdf';
/*Add text in Header/Footer of a PDF-file and save the "ResultAddHeaderFooter.pdf"*/
const json = AsposePdfModule.AsposePdfAddTextHeaderFooter(pdf_file, "Aspose.PDF for Node.js via C++ via C++", "ASPOSE", "ResultAddHeaderFooter.pdf");
console.log("AsposePdfAddTextHeaderFooter => %O", json.errorCode == 0 ? json.fileNameResult : json.errorText);
```