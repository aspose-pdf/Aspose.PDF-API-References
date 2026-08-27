---
title: "PdfPageEditor.GetPageBoxSize"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfPageEditor. Mengembalikan ukuran kotak yang ditentukan dalam dokumen"
type: docs
weight: 130
url: /id/net/aspose.pdf.facades/pdfpageeditor/getpageboxsize/
---
## PdfPageEditor.GetPageBoxSize method

Mengembalikan ukuran kotak yang ditentukan dalam document.

```csharp
public Rectangle GetPageBoxSize(int page, string pageBoxName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| halaman | Int32 | Indeks halaman. Halaman dokumen diberi nomor mulai dari 1. |
| pageBoxName | String | Nama tipe kotak. Nilai yang valid adalah: "art", "bleed", "crop", "media", "trim". |

### Nilai Kembalian

Rectangle yang berisi kotak yang diminta.

## Contoh

Contoh berikut menunjukkan cara mendapatkan media box dari halaman pertama:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
System.Drawing.Rectangle rect = editor.GetBoxSize(1, "media");
```

### Lihat Juga

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


