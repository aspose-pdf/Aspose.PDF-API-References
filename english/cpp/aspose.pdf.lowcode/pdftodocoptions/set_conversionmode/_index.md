---
title: Aspose::Pdf::LowCode::PdfToDocOptions::set_ConversionMode method
linktitle: set_ConversionMode
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LowCode::PdfToDocOptions::set_ConversionMode method. Allows to control how a PDF document is converted into a word processing document in C++.'
type: docs
weight: 500
url: /cpp/aspose.pdf.lowcode/pdftodocoptions/set_conversionmode/
---
## PdfToDocOptions::set_ConversionMode method


Allows to control how a PDF document is converted into a word processing document.

```cpp
void Aspose::Pdf::LowCode::PdfToDocOptions::set_ConversionMode(Aspose::Pdf::LowCode::ConversionMode value)
```

## Remarks


Use the [ConversionMode::TextBox](../../conversionmode/) mode when the resulting document is not going to be heavily edited further. Textboxes are easy to modify when there is not a lot to do.

Use the [ConversionMode::Flow](../../conversionmode/) mode when the output document needs further editing. [Paragraphs](../../../aspose.pdf/paragraphs/) and text lines in the flow mode allow easy modification of text, but unsupported formatting objects will look worse than in the [ConversionMode::TextBox](../../conversionmode/) mode.
## See Also

* Enum [ConversionMode](../../conversionmode/)
* Class [PdfToDocOptions](../)
* Namespace [Aspose::Pdf::LowCode](../../)
* Library [Aspose.PDF for C++](../../../)
