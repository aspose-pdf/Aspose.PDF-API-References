---
title: "PdfContentEditor.CreateText"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfContentEditor. Membuat anotasi teks dalam dokumen PDF"
type: docs
weight: 290
url: /id/net/aspose.pdf.facades/pdfcontenteditor/createtext/
---
## PdfContentEditor.CreateText method

Membuat anotasi teks dalam dokumen PDF

```csharp
public void CreateText(Rectangle rect, string title, string contents, bool open, string icon, 
    int page)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | Rectangle | Persegi panjang anotasi yang menentukan lokasi anotasi pada halaman. |
| title | String | Judul anotasi. |
| isi | String | Isi anotasi. |
| buka | Boolean | Bendera yang menentukan apakah anotasi harus ditampilkan terbuka pada awalnya. |
| ikon | String | Nama ikon yang akan digunakan dalam menampilkan anotasi. Nilai ini dapat berupa: "Comment", "Key", "Note", "Help", "NewParagraph", "Paragraph", "Insert" |
| halaman | Int32 | Nomor halaman asli tempat anotasi teks akan dibuat. |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateText(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "You are welcome to Aspose!", true, "Key", 1);
editor.Save("example_out.pdf");
```

### Lihat Juga

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


