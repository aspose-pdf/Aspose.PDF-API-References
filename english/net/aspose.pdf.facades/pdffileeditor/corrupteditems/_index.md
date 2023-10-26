---
title: PdfFileEditor.CorruptedItems
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor property. Array of encountered problems when concatenation was performed. For every corrupted document from passed to Concatenate function new CorruptedItem entry is created. This property may be used only when CorruptedFileAction is ConcatenateIgnoringCorrupted
type: docs
weight: 110
url: /net/aspose.pdf.facades/pdffileeditor/corrupteditems/
---
## PdfFileEditor.CorruptedItems property

Array of encountered problems when concatenation was performed. For every corrupted document from passed to Concatenate() function new CorruptedItem entry is created. This property may be used only when CorruptedFileAction is ConcatenateIgnoringCorrupted.

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

### See Also

* class [CorruptedItem](../../pdffileeditor.corrupteditem/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


