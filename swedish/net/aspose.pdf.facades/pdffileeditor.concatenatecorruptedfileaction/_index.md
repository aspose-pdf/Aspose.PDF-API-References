---
title: Enum PdfFileEditor.ConcatenateCorruptedFileAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileEditorConcatenateCorruptedFileAction enum. Åtgärd som utförs när en korrupt fil möttes i sammanfogningsprocessen
type: docs
weight: 4470
url: /sv/net/aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
## PdfFileEditor.ConcatenateCorruptedFileAction enumeration

Åtgärd som utförs när en korrupt fil möttes i sammanfogningsprocessen.

```csharp
public enum ConcatenateCorruptedFileAction
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| StopWithError | `0` | Om en korrupt fil möttes, stoppa sammanfogningsprocessen och returnera ett fel. |
| ConcatenateIgnoringCorrupted | `1` | Om en korrupt fil möttes, stoppa inte sammanfogningen och bearbeta inte den korrupta filen. Lista över korrupta filer är tillgänglig i Failures-egenskapen. |
| ConcatenateIgnoringCorruptedObjects | `2` | När ett korrupt objekt möts i källdokumentet, stoppas inte processen och det korrupta objektet ignoreras endast. |

### Se Även

* klass [PdfFileEditor](../pdffileeditor/)
* namnrymd [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../)