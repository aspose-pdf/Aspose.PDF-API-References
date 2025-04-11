---
title: PdfFileEditor.CorruptedItems
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-Eigenschaft. Array von aufgetretenen Problemen, wenn die Verkettung durchgeführt wurde. Für jedes beschädigte Dokument, das an die Concatenate-Funktion übergeben wurde, wird ein neuer CorruptedItem-Eintrag erstellt. Diese Eigenschaft kann nur verwendet werden, wenn CorruptedFileAction ConcatenateIgnoringCorrupted ist.
type: docs
weight: 90
url: /de/net/aspose.pdf.facades/pdffileeditor/corrupteditems/
---
## PdfFileEditor.CorruptedItems-Eigenschaft

Array von aufgetretenen Problemen, wenn die Verkettung durchgeführt wurde. Für jedes beschädigte Dokument, das an die Concatenate() Funktion übergeben wurde, wird ein neuer CorruptedItem-Eintrag erstellt. Diese Eigenschaft kann nur verwendet werden, wenn CorruptedFileAction ConcatenateIgnoringCorrupted ist.

```csharp
//concatenate documents and show information about corrupted documents
PdfFileEditor pfe = new PdfFileEditor();
pfe.CorruptedFileAction = PdfFileEditor.ConcatenateCorruptedFileActions.ConcatenateIgnoringCorrupted;
if (pfe.CorruptedItems.Length >0)
{
  foreach(PdfFileEditor.CorruptedItem item in pfe.CorruptedItems)
  {
     Console.WriteLine(item.Index + " reason: " + item.Exception);
  }
}
```

```csharp
public CorruptedItem[] CorruptedItems { get; }
```

### Siehe auch

* Klasse [CorruptedItem](../../pdffileeditor.corrupteditem/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)