---
title: PdfFormatConversionOptions.PuaProcessingStrategy
second_title: Aspose.PDF for Java API Reference
description: Some PDF documents have special unicode symbols which are belonged to Private Use Area PUA see description at https//en.wikipedia.org/wiki/Private_Use_Areas.
type: docs
weight: 11
url: /java/com.aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public static final class PdfFormatConversionOptions.PuaProcessingStrategy extends System.Enum
```

Some PDF documents have special unicode symbols, which are belonged to Private Use Area (PUA), see description at https://en.wikipedia.org/wiki/Private\_Use\_Areas. This symbols cause an PDF/A compliant errors like "Text is mapped to Unicode Private Use Area but no ActualText entry is present". This enumeration declares a strategies which can be used to handle PUA symbols.
## Fields

| Field | Description |
| --- | --- |
| [None](#None) | Disable PUA symbol processing. |
| [SurroundPuaTextWithEmptyActualText](#SurroundPuaTextWithEmptyActualText) | Inserts marked content block with ActualText entry which contains empty text. |
| [SubstitutePuaSymbols](#SubstitutePuaSymbols) | This strategy works slower than 'SurroundPuaTextWithEmptyActualText' but it can remove PUA compliant errors for documents which can't be handled properly by SurroundPuaTextWithEmptyActualText. |
### None {#None}
```
public static final int None
```


Disable PUA symbol processing. This strategy used by default for PDF/A documents with Level B conformance.

### SurroundPuaTextWithEmptyActualText {#SurroundPuaTextWithEmptyActualText}
```
public static final int SurroundPuaTextWithEmptyActualText
```


Inserts marked content block with ActualText entry which contains empty text. This strategy gives good results for documents without marked content blocks. Used by default for PDF/A documents with Level A conformance.

### SubstitutePuaSymbols {#SubstitutePuaSymbols}
```
public static final int SubstitutePuaSymbols
```


This strategy works slower than 'SurroundPuaTextWithEmptyActualText' but it can remove PUA compliant errors for documents which can't be handled properly by SurroundPuaTextWithEmptyActualText. PUA symbols are substituted on symbol 'space' or special unicode (some PUA symbols have unicode analogs). Substitution applied not to document's text but to font's internal data ToUnicode so it doesn't affects symbol's vision but it affects symbol's presentation in copy/paste operation system buffer.

