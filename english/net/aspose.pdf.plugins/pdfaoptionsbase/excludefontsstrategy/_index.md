---
title: PdfAOptionsBase.ExcludeFontsStrategy
second_title: Aspose.PDF for .NET API Reference
description: PdfAOptionsBase property. Gets or sets the strategy for removing fonts to minimize the output file size during the PDF/A conversion process
type: docs
weight: 30
url: /net/aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/
---
## PdfAOptionsBase.ExcludeFontsStrategy property

Gets or sets the strategy for removing fonts to minimize the output file size during the PDF/A conversion process.

```csharp
public RemoveFontsStrategy ExcludeFontsStrategy { get; set; }
```

### Property Value

The strategy for removing fonts. This can be one of the values from the [`RemoveFontsStrategy`](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/) enumeration. The default is the combination of SubsetFonts and RemoveDuplicatedFonts.

## Remarks

This property allows you to control how fonts are handled during the conversion process. You can choose to remove duplicated fonts, remove similar fonts with different widths, or subset fonts.

### See Also

* enum [RemoveFontsStrategy](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/)
* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)


