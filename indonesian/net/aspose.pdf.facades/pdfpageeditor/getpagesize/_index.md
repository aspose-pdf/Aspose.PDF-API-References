---
title: PdfPageEditor.GetPageSize
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfPageEditor. Mengembalikan ukuran halaman dari halaman yang ditentukan
type: docs
weight: 160
url: /id/net/aspose.pdf.facades/pdfpageeditor/getpagesize/
---
## Metode PdfPageEditor.GetPageSize

Mengembalikan ukuran halaman dari halaman yang ditentukan.

```csharp
public PageSize GetPageSize(int page)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| page | Int32 | Indeks halaman. Halaman dokumen diberi nomor mulai dari 1. |

### Nilai Kembali

Hasil adalah instance dari PageSize. Gunakan properti Width dan Height dari objek yang dikembalikan untuk mendapatkan lebar dan tinggi halaman.

## Contoh

Contoh berikut menunjukkan penggunaan metode GetPageSize:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
PageSize size = editor.GetPageSize(1);
Console.WriteLine("Size of 1st page : " + size.Width + " x " + size.Height);
```

### Lihat Juga

* kelas [PageSize](../../../aspose.pdf/pagesize/)
* kelas [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)