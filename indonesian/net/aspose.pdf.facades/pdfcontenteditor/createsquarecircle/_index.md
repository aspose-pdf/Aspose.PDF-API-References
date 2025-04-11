---
title: PdfContentEditor.CreateSquareCircle
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfContentEditor. Membuat anotasi persegi-lingkaran
type: docs
weight: 280
url: /id/net/aspose.pdf.facades/pdfcontenteditor/createsquarecircle/
---
## Metode PdfContentEditor.CreateSquareCircle

Membuat anotasi persegi-lingkaran.

```csharp
public void CreateSquareCircle(Rectangle rect, string contents, Color clr, bool square, int page, 
    int borderWidth)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | Rectangle | Persegi panjang anotasi yang mendefinisikan lokasi anotasi di halaman. |
| contents | String | Isi dari anotasi. |
| clr | Color | Warna persegi atau lingkaran. |
| square | Boolean | Benar (persegi), salah (lingkaran). |
| page | Int32 | Nomor halaman asli tempat anotasi akan dibuat. |
| borderWidth | Int32 | Lebar batas dari persegi atau lingkaran. |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateSquareCircle(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, false, 1, 5);
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)