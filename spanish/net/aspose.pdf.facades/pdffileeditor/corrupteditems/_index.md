---
title: PdfFileEditor.CorruptedItems
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de PdfFileEditor. Array de problemas encontrados cuando se realizó la concatenación. Para cada documento corrupto pasado a la función Concatenate, se crea una nueva entrada CorruptedItem. Esta propiedad solo puede ser utilizada cuando CorruptedFileAction es ConcatenateIgnoringCorrupted
type: docs
weight: 90
url: /es/net/aspose.pdf.facades/pdffileeditor/corrupteditems/
---
## Propiedad PdfFileEditor.CorruptedItems

Array de problemas encontrados cuando se realizó la concatenación. Para cada documento corrupto pasado a la función Concatenate() se crea una nueva entrada CorruptedItem. Esta propiedad solo puede ser utilizada cuando CorruptedFileAction es ConcatenateIgnoringCorrupted.

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

### Ver También

* clase [CorruptedItem](../../pdffileeditor.corrupteditem/)
* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)