---
title: PdfFileEditor.CorruptedItems
second_title: Aspose.PDF for .NET API Reference
description: Properti PdfFileEditor. Array masalah yang dihadapi saat penggabungan dilakukan. Untuk setiap dokumen yang rusak dari yang diteruskan ke fungsi Concatenate, entri CorruptedItem baru dibuat. Properti ini hanya dapat digunakan ketika CorruptedFileAction adalah ConcatenateIgnoringCorrupted
type: docs
weight: 90
url: /id/net/aspose.pdf.facades/pdffileeditor/corrupteditems/
---
## Properti PdfFileEditor.CorruptedItems

Array masalah yang dihadapi saat penggabungan dilakukan. Untuk setiap dokumen yang rusak dari yang diteruskan ke fungsi Concatenate() entri CorruptedItem baru dibuat. Properti ini hanya dapat digunakan ketika CorruptedFileAction adalah ConcatenateIgnoringCorrupted.

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

### Lihat Juga

* kelas [CorruptedItem](../../pdffileeditor.corrupteditem/)
* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)