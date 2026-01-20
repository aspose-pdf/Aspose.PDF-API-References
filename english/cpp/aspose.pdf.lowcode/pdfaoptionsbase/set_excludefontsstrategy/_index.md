---
title: Aspose::Pdf::LowCode::PdfAOptionsBase::set_ExcludeFontsStrategy method
linktitle: set_ExcludeFontsStrategy
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LowCode::PdfAOptionsBase::set_ExcludeFontsStrategy method. Sets the strategy for removing fonts to minimize the output file size during the PDF/A conversion process in C++.'
type: docs
weight: 2000
url: /cpp/aspose.pdf.lowcode/pdfaoptionsbase/set_excludefontsstrategy/
---
## PdfAOptionsBase::set_ExcludeFontsStrategy method


Sets the strategy for removing fonts to minimize the output file size during the PDF/A conversion process.

```cpp
void Aspose::Pdf::LowCode::PdfAOptionsBase::set_ExcludeFontsStrategy(PdfFormatConversionOptions::RemoveFontsStrategy value)
```

## Remarks


The strategy for removing fonts. This can be one of the values from the [PdfFormatConversionOptions::RemoveFontsStrategy](../../../aspose.pdf/pdfformatconversionoptions/removefontsstrategy/) enumeration. The default is the combination of [PdfFormatConversionOptions::RemoveFontsStrategy::SubsetFonts](../../../aspose.pdf/pdfformatconversionoptions/removefontsstrategy/) and [PdfFormatConversionOptions::RemoveFontsStrategy::RemoveDuplicatedFonts](../../../aspose.pdf/pdfformatconversionoptions/removefontsstrategy/). 

This property allows you to control how fonts are handled during the conversion process. You can choose to remove duplicated fonts, remove similar fonts with different widths, or subset fonts. 
## See Also

* Enum [RemoveFontsStrategy](../../../aspose.pdf/pdfformatconversionoptions/removefontsstrategy/)
* Class [PdfAOptionsBase](../)
* Namespace [Aspose::Pdf::LowCode](../../)
* Library [Aspose.PDF for C++](../../../)
