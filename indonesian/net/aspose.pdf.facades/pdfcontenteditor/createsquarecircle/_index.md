---
title: "PdfContentEditor.CreateSquareCircle"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfContentEditor. Membuat anotasi squarecircle"
type: docs
weight: 280
url: /id/net/aspose.pdf.facades/pdfcontenteditor/createsquarecircle/
---
## PdfContentEditor.CreateSquareCircle method

Membuat anotasi persegi-lingkaran.

```csharp
public void CreateSquareCircle(Rectangle rect, string contents, Color clr, bool square, int page, 
    int borderWidth)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | Rectangle | Persegi panjang anotasi yang menentukan lokasi anotasi pada halaman. |
| isi | String | Isi anotasi. |
| clr | Color | Warna persegi atau lingkaran. |
| persegi | Boolean | True (persegi), false (lingkaran). |
| halaman | Int32 | Jumlah halaman asli tempat anotasi akan dibuat. |
| borderWidth | Int32 | Lebar batas persegi atau lingkaran. |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateSquareCircle(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, false, 1, 5);
editor.Save("example_out.pdf");
```

### Lihat Juga

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


