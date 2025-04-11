---
title: PdfFileEditor.CorruptedItems
second_title: Aspose.PDF for .NET API Reference
description: Propriedade PdfFileEditor. Array de problemas encontrados quando a concatenação foi realizada. Para cada documento corrompido passado para a função Concatenate, uma nova entrada CorruptedItem é criada. Esta propriedade pode ser usada apenas quando CorruptedFileAction é ConcatenateIgnoringCorrupted
type: docs
weight: 90
url: /pt/net/aspose.pdf.facades/pdffileeditor/corrupteditems/
---
## Propriedade PdfFileEditor.CorruptedItems

Array de problemas encontrados quando a concatenação foi realizada. Para cada documento corrompido passado para a função Concatenate() uma nova entrada CorruptedItem é criada. Esta propriedade pode ser usada apenas quando CorruptedFileAction é ConcatenateIgnoringCorrupted.

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

### Veja Também

* classe [CorruptedItem](../../pdffileeditor.corrupteditem/)
* classe [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)