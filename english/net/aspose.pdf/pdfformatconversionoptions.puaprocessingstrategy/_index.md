---
title: Enum PdfFormatConversionOptions.PuaProcessingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfFormatConversionOptionsPuaProcessingStrategy enum. Some PDF documents have special unicode symbols which are belonged to Private Use Area PUA see description at https//en.wikipedia.org/wiki/Private_Use_Areas. This symbols cause an PDF/A compliant errors like Text is mapped to Unicode Private Use Area but no ActualText entry is present. This enumeration declares a strategies which can be used to handle PUA symbols
type: docs
weight: 8300
url: /net/aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
## PdfFormatConversionOptions.PuaProcessingStrategy enumeration

Some PDF documents have special unicode symbols, which are belonged to Private Use Area (PUA), see description at https://en.wikipedia.org/wiki/Private_Use_Areas. This symbols cause an PDF/A compliant errors like "Text is mapped to Unicode Private Use Area but no ActualText entry is present". This enumeration declares a strategies which can be used to handle PUA symbols.

```csharp
public enum PuaProcessingStrategy
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | Disable PUA symbol processing. This strategy used by default for PDF/A documents with Level B conformance. |
| SurroundPuaTextWithEmptyActualText | `1` | Inserts marked content block with ActualText entry which contains empty text. This strategy gives good results for documents without marked content blocks. Used by default for PDF/A documents with Level A conformance. |
| SubstitutePuaSymbols | `2` | This strategy works slower than 'SurroundPuaTextWithEmptyActualText' but it can remove PUA compliant errors for documents which can't be handled properly by SurroundPuaTextWithEmptyActualText. PUA symbols are substituted on symbol 'space' or special unicode (some PUA symbols have unicode analogs). Substitution applied not to document's text but to font's internal data ToUnicode so it doesn't affects symbol's vision but it affects symbol's presentation in copy/paste operation system buffer. |

### See Also

* class [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


