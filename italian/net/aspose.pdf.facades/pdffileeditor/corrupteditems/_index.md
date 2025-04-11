---
title: PdfFileEditor.CorruptedItems
second_title: Aspose.PDF for .NET API Reference
description: Proprietà di PdfFileEditor. Array di problemi riscontrati quando è stata eseguita la concatenazione. Per ogni documento corrotto passato alla funzione Concatenate viene creata una nuova voce CorruptedItem. Questa proprietà può essere utilizzata solo quando CorruptedFileAction è ConcatenateIgnoringCorrupted
type: docs
weight: 90
url: /it/net/aspose.pdf.facades/pdffileeditor/corrupteditems/
---
## Proprietà PdfFileEditor.CorruptedItems

Array di problemi riscontrati quando è stata eseguita la concatenazione. Per ogni documento corrotto passato alla funzione Concatenate() viene creata una nuova voce CorruptedItem. Questa proprietà può essere utilizzata solo quando CorruptedFileAction è ConcatenateIgnoringCorrupted.

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

### Vedi Anche

* classe [CorruptedItem](../../pdffileeditor.corrupteditem/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)