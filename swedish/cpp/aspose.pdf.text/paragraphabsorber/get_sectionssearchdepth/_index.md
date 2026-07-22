---
title: "Aspose::Pdf::Text::ParagraphAbsorber::get_SectionsSearchDepth method"
linktitle: "get_SectionsSearchDepth"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::ParagraphAbsorber::get_SectionsSearchDepth metoden. Hämtar värdet som instruerar hur många gånger sekventiella sökningar efter finare strukturelement ska utföras. Standard sökdjup är 3. Det betyder tre sökningar för horisontellt delade sektioner (rubriker, stycken osv) och tre sökningar för vertikalt delade (kolumner) i C++."
type: docs
weight: 500
url: /sv/cpp/aspose.pdf.text/paragraphabsorber/get_sectionssearchdepth/
---
## ParagraphAbsorber::get_SectionsSearchDepth method


Hämtar värdet som anger hur många gånger sekventiella sökningar efter finare strukturelement ska utföras. Standard sökdjup är 3. Det innebär tre sökningar för horisontellt delade sektioner (rubriker, stycken osv) och tre sökningar för vertikalt delade (kolumner).

```cpp
int32_t Aspose::Pdf::Text::ParagraphAbsorber::get_SectionsSearchDepth() const
```

## Anmärkningar


Att öka detta värde kan leda till en liten prestandaförsämring utan synliga förändringar i sökresultatet. Att minska detta värde kan leda till felaktig identifiering av stycken i sektioner. Vi rekommenderar inte att sätta värdet lägre än standard om du inte önskar få endast 'grova' element av sidstrukturen.
## Se även

* Class [ParagraphAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
