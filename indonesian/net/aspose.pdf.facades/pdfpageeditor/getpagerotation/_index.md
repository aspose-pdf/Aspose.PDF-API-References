---
title: PdfPageEditor.GetPageRotation
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfPageEditor. Mengembalikan rotasi halaman yang ditentukan
type: docs
weight: 140
url: /id/net/aspose.pdf.facades/pdfpageeditor/getpagerotation/
---
## Metode PdfPageEditor.GetPageRotation

Mengembalikan rotasi halaman yang ditentukan.

```csharp
public int GetPageRotation(int page)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| page | Int32 | Indeks halaman. Halaman dokumen diberi nomor mulai dari 1. |

### Nilai Kembali

Rotasi halaman dalam derajat.

## Contoh

Contoh berikut menunjukkan cara mendapatkan rotasi halaman:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
int rotation = editor.GetPageSize(1);
Console.WriteLine("Rotation of 1st page : " + rotation + " degrees");        
```

### Lihat Juga

* kelas [PdfPageEditor](../)
* ruang nama [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)