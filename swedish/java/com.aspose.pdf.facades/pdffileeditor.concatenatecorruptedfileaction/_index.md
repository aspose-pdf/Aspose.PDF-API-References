---
title: "PdfFileEditor.ConcatenateCorruptedFileAction"
linktitle: "PdfFileEditor.ConcatenateCorruptedFileAction"
second_title: "Aspose.PDF för Java API-referens"
description: "Åtgärd som utförs när en korrupt fil påträffas i sammanslagningsprocessen."
type: docs
weight: 420
url: /sv/java/com.aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction, com.aspose.ms.System.Enum, com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction

```
public static final class PdfFileEditor.ConcatenateCorruptedFileAction extends com.aspose.ms.System.Enum
```

Åtgärd som utförs när en korrupt fil påträffas i sammanslagningsprocessen.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [ConcatenateIgnoringCorrupted](#ConcatenateIgnoringCorrupted) | Om en korrupt fil påträffades, stoppa då inte sammanslagningen och bearbeta inte den korrupta filen. Listan över korrupta filer är tillgänglig i egenskapen Failures. |
| [ConcatenateIgnoringCorruptedObjects](#ConcatenateIgnoringCorruptedObjects) | När ett korrupt objekt påträffas i källdokumentet, kommer processen inte att stoppas och endast det korrupta objektet ignoreras. |
| [StopWithError](#StopWithError) | Om en korrupt fil påträffas, stoppa då sammanslagningsprocessen och returnera ett fel. |

### ConcatenateIgnoringCorrupted {#ConcatenateIgnoringCorrupted}
```
public static final int ConcatenateIgnoringCorrupted
```

Om en korrupt fil påträffades, stoppa då inte sammanslagningen och bearbeta inte den korrupta filen. Listan över korrupta filer är tillgänglig i egenskapen Failures.

### ConcatenateIgnoringCorruptedObjects {#ConcatenateIgnoringCorruptedObjects}
```
public static final int ConcatenateIgnoringCorruptedObjects
```

När ett korrupt objekt påträffas i källdokumentet, kommer processen inte att stoppas och endast det korrupta objektet ignoreras.

### StopWithError {#StopWithError}
```
public static final int StopWithError
```

Om en korrupt fil påträffas, stoppa då sammanslagningsprocessen och returnera ett fel.
