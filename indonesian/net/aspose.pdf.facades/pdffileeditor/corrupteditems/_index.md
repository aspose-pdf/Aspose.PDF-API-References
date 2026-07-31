---
title: "PdfFileEditor.CorruptedItems"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "PdfFileEditor property. Array dari masalah yang ditemui saat penggabungan dilakukan. Untuk setiap dokumen rusak yang diteruskan ke fungsi Concatenate, entri CorruptedItem baru dibuat. Properti ini hanya dapat digunakan ketika CorruptedFileAction adalah ConcatenateIgnoringCorrupted."
type: docs
weight: 90
url: /id/net/aspose.pdf.facades/pdffileeditor/corrupteditems/
---
## PdfFileEditor.CorruptedItems property

Array masalah yang ditemui saat penggabungan dilakukan. Untuk setiap dokumen rusak yang diberikan ke fungsi Concatenate() dibuat entri CorruptedItem baru. Properti ini hanya dapat digunakan ketika CorruptedFileAction adalah ConcatenateIgnoringCorrupted.

```csharp
//gabungkan dokumen dan tampilkan informasi tentang dokumen yang rusak
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

* class [CorruptedItem](../../pdffileeditor.corrupteditem/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


