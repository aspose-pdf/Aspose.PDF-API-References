---
title: Aspose::Pdf::LowCode::PdfAOptionsBase::get_ExcludeFontsStrategy method
linktitle: get_ExcludeFontsStrategy
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LowCode::PdfAOptionsBase::get_ExcludeFontsStrategy method. Gets the strategy for removing fonts to minimize the output file size during the PDF/A conversion process in C++.'
type: docs
weight: 500
url: /cpp/aspose.pdf.lowcode/pdfaoptionsbase/get_excludefontsstrategy/
---
## PdfAOptionsBase::get_ExcludeFontsStrategy method


Gets the strategy for removing fonts to minimize the output file size during the PDF/A conversion process.

```cpp
PdfFormatConversionOptions::RemoveFontsStrategy Aspose::Pdf::LowCode::PdfAOptionsBase::get_ExcludeFontsStrategy()
```

## Remarks


The strategy for removing fonts. This can be one of the values from the [PdfFormatConversionOptions::RemoveFontsStrategy](../../../aspose.pdf/pdfformatconversionoptions/removefontsstrategy/) enumeration. The default is the combination of [PdfFormatConversionOptions::RemoveFontsStrategy::SubsetFonts](../../../aspose.pdf/pdfformatconversionoptions/removefontsstrategy/) and [PdfFormatConversionOptions::RemoveFontsStrategy::RemoveDuplicatedFonts](../../../aspose.pdf/pdfformatconversionoptions/removefontsstrategy/). 

This property allows you to control how fonts are handled during the conversion process. You can choose to remove duplicated fonts, remove similar fonts with different widths, or subset fonts. 
## See Also

* Enum [RemoveFontsStrategy](../../../aspose.pdf/pdfformatconversionoptions/removefontsstrategy/)
* Class [PdfAOptionsBase](../)
* Namespace [Aspose::Pdf::LowCode](../../)
* Library [Aspose.PDF for C++](../../../)
