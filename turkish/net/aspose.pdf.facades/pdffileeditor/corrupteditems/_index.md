---
title: PdfFileEditor.CorruptedItems
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor özelliği. Birleştirme işlemi gerçekleştirildiğinde karşılaşılan sorunların dizisi. Concatenate fonksiyonuna geçirilen her bozuk belge için yeni bir CorruptedItem girişi oluşturulur. Bu özellik yalnızca CorruptedFileAction ConcatenateIgnoringCorrupted olduğunda kullanılabilir.
type: docs
weight: 90
url: /tr/net/aspose.pdf.facades/pdffileeditor/corrupteditems/
---
## PdfFileEditor.CorruptedItems özelliği

Birleştirme işlemi gerçekleştirildiğinde karşılaşılan sorunların dizisi. Concatenate() fonksiyonuna geçirilen her bozuk belge için yeni bir CorruptedItem girişi oluşturulur. Bu özellik yalnızca CorruptedFileAction ConcatenateIgnoringCorrupted olduğunda kullanılabilir.

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

### Ayrıca Bakınız

* sınıf [CorruptedItem](../../pdffileeditor.corrupteditem/)
* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)