---
title: PdfContentEditor.CreatePopup
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfContentEditor. Membuat anotasi pop-up dalam dokumen PDF
type: docs
weight: 250
url: /id/net/aspose.pdf.facades/pdfcontenteditor/createpopup/
---
## Metode PdfContentEditor.CreatePopup

Membuat anotasi pop-up dalam dokumen PDF.

```csharp
public void CreatePopup(Rectangle rect, string contents, bool open, int page)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | Rectangle | Persegi panjang anotasi yang mendefinisikan lokasi anotasi di halaman. |
| contents | String | Isi dari anotasi. |
| open | Boolean | Sebuah flag yang menentukan apakah anotasi pop-up harus ditampilkan terbuka pada awalnya. |
| page | Int32 | Nomor halaman asli tempat anotasi akan dibuat. |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePopup(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", true, 1);
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)