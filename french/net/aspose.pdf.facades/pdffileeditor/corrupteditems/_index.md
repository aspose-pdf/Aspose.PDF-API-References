---
title: PdfFileEditor.CorruptedItems
second_title: Aspose.PDF for .NET API Reference
description: Propriété PdfFileEditor. Tableau des problèmes rencontrés lors de la concaténation. Pour chaque document corrompu passé à la fonction Concatenate, une nouvelle entrée CorruptedItem est créée. Cette propriété ne peut être utilisée que lorsque CorruptedFileAction est ConcatenateIgnoringCorrupted
type: docs
weight: 90
url: /fr/net/aspose.pdf.facades/pdffileeditor/corrupteditems/
---
## Propriété PdfFileEditor.CorruptedItems

Tableau des problèmes rencontrés lors de la concaténation. Pour chaque document corrompu passé à la fonction Concatenate() une nouvelle entrée CorruptedItem est créée. Cette propriété ne peut être utilisée que lorsque CorruptedFileAction est ConcatenateIgnoringCorrupted.

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

### Voir aussi

* classe [CorruptedItem](../../pdffileeditor.corrupteditem/)
* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)