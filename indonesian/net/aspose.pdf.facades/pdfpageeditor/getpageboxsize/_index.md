---
title: PdfPageEditor.GetPageBoxSize
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfPageEditor. Mengembalikan ukuran kotak yang ditentukan dalam dokumen
type: docs
weight: 130
url: /id/net/aspose.pdf.facades/pdfpageeditor/getpageboxsize/
---
## Metode PdfPageEditor.GetPageBoxSize

Mengembalikan ukuran kotak yang ditentukan dalam dokumen.

```csharp
public Rectangle GetPageBoxSize(int page, string pageBoxName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| page | Int32 | Indeks halaman. Halaman dokumen diberi nomor mulai dari 1. |
| pageBoxName | String | Nama tipe kotak. Nilai yang valid adalah: "art", "bleed", "crop", "media", "trim". |

### Nilai Kembali

Rectangle yang berisi kotak yang diminta.

## Contoh

Contoh berikut menunjukkan cara mendapatkan kotak media dari halaman ke-1:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
System.Drawing.Rectangle rect = editor.GetBoxSize(1, "media");
```

### Lihat Juga

* kelas [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)