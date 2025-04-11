---
title: PdfFileEditor.CorruptedItems
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-egenskap. Array av upptäckta problem när sammanfogning utfördes. För varje korrupt dokument från som passerades till Concatenate-funktionen skapas en ny CorruptedItem-post. Denna egenskap kan endast användas när CorruptedFileAction är ConcatenateIgnoringCorrupted
type: docs
weight: 90
url: /sv/net/aspose.pdf.facades/pdffileeditor/corrupteditems/
---
## PdfFileEditor.CorruptedItems-egenskap

Array av upptäckta problem när sammanfogning utfördes. För varje korrupt dokument från som passerades till Concatenate() funktionen skapas en ny CorruptedItem-post. Denna egenskap kan endast användas när CorruptedFileAction är ConcatenateIgnoringCorrupted.

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

### Se Även

* klass [CorruptedItem](../../pdffileeditor.corrupteditem/)
* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)