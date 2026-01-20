---
title: Aspose::Pdf::PdfFormatConversionOptions::RemoveFontsStrategy enum
linktitle: RemoveFontsStrategy
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::PdfFormatConversionOptions::RemoveFontsStrategy enum. Some documens have large size after converison into PDF/A format. To reduce file size for these documents it''s necessary to define a strategy of fonts removing. This enumeration declares a strategies which can be used to optimize fonts usage. Every strategy from this enumeration has sense only when flag OptimizeFileSize is set in C++.'
type: docs
weight: 4300
url: /cpp/aspose.pdf/pdfformatconversionoptions/removefontsstrategy/
---
## RemoveFontsStrategy enum


Some documens have large size after converison into PDF/A format. To reduce file size for these documents it's necessary to define a strategy of fonts removing. This enumeration declares a strategies which can be used to optimize fonts usage. Every strategy from this enumeration has sense only when flag [OptimizeFileSize](../) is set.

```cpp
enum class RemoveFontsStrategy : uint8_t
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| RemoveDuplicatedFonts | 4 | This strategy removes all the fonts which have duplicates in document. If document contains group of duplicated fonts only one font from this group is embedded in document. All other fonts from this group are removed from document, every removed font substituted with the already embedded analog. |
| RemoveSimilarFontsWithDifferentWidths | 1 | This strategy looks like [RemoveDuplicatedFonts](./) but it removes not fully duplicated fonts but fonts which are similar one to another and differs only by parameter "Widths". This parameter contains set of some widths for specified symbols of font. Every value of width from this "Widths" set is not the real width of symbol(glyph), real width for this symbol already defined in font's binary data. Value of width from "Widths" set means visual width for this symbol - the width which PDF viewer software must set on displaying symbol instead of real width defined in the font. More accurately specification tells: Acrobat 5.0 and later viewers use the glyph widths stored in the font dictionary to override the widths of glyphs in the font program itself, which improves the consistency of the display and printing of the document. This strategy is more effective than [RemoveDuplicatedFonts](./) but using of this strategy in some cases theoretically could damage visual presentation of converted document. This defect is possible due to that declared widths of fonts could be different for the same symbol and in this case width of this symbol will be changed to new one after font substitution - when removed font will be replaced in document with already embedded one. And if symbol's visual width will be changed - it will be shown incorrectly and this distinction could cause visual defects such as text overlapping or another problems. But visual defect described is a very rare case and this strategy reduces size of document more effectively. |
| SubsetFonts | 2 | This is most effective strategy to reduce document's size. It takes fully embedded font sets and trim them down to only the subsets used. It's recommended to use this strategy in combination with [RemoveDuplicatedFonts](./) or [RemoveSimilarFontsWithDifferentWidths](./) to get multiple compression effect for file size. Using of all three strategies simultaneously has no sense and strategy [RemoveSimilarFontsWithDifferentWidths](./) will not be used in this case. |

## See Also

* Class [PdfFormatConversionOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
