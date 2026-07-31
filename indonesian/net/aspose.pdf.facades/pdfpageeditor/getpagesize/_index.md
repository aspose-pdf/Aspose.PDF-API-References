---
title: "PdfPageEditor.GetPageSize"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfPageEditor. Mengembalikan ukuran halaman dari halaman yang ditentukan"
type: docs
weight: 160
url: /id/net/aspose.pdf.facades/pdfpageeditor/getpagesize/
---
## PdfPageEditor.GetPageSize method

Mengembalikan ukuran halaman dari halaman yang ditentukan.

```csharp
public PageSize GetPageSize(int page)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| halaman | Int32 | Indeks halaman. Halaman dokumen diberi nomor mulai dari 1. |

### Nilai Kembalian

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

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


