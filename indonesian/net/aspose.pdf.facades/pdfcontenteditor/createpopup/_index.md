---
title: "PdfContentEditor.CreatePopup"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfContentEditor. Membuat anotasi popup dalam dokumen PDF"
type: docs
weight: 250
url: /id/net/aspose.pdf.facades/pdfcontenteditor/createpopup/
---
## PdfContentEditor.CreatePopup method

Membuat anotasi popup dalam dokumen PDF.

```csharp
public void CreatePopup(Rectangle rect, string contents, bool open, int page)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | Rectangle | Persegi panjang anotasi yang menentukan lokasi anotasi pada halaman. |
| isi | String | Isi anotasi. |
| buka | Boolean | Bendera yang menentukan apakah anotasi pop-up harus ditampilkan terbuka pada awalnya. |
| halaman | Int32 | Jumlah halaman asli tempat anotasi akan dibuat. |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePopup(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", true, 1);
editor.Save("example_out.pdf");
```

### Lihat Juga

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


