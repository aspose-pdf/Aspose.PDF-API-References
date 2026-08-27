---
title: "Enum PdfFileEditor.ConcatenateCorruptedFileAction"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Facades.PdfFileEditorConcatenateCorruptedFileAction enum. Åtgärd som utförs när en korrupt fil påträffas i sammanslagningsprocessen"
type: docs
weight: 4590
url: /sv/net/aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
## PdfFileEditor.ConcatenateCorruptedFileAction enumeration

Åtgärd som utförs när en korrupt fil påträffas i sammanslagningsprocessen.

```csharp
public enum ConcatenateCorruptedFileAction
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| StopWithError | `0` | Om en korrupt fil påträffas, stoppa då sammanslagningsprocessen och returnera ett fel. |
| ConcatenateIgnoringCorrupted | `1` | Om en korrupt fil påträffas, stoppa då inte sammanslagningen och bearbeta inte den korrupta filen. Lista över korrupta filer är tillgänglig i egenskapen Failures. |
| ConcatenateIgnoringCorruptedObjects | `2` | När ett korrupt objekt påträffas i källdokumentet, kommer processen inte att stoppas och endast det korrupta objektet ignoreras. |

### Se även

* class [PdfFileEditor](../pdffileeditor/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


