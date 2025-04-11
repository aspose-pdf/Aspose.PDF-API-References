---
title: PdfContentEditor.CreateFreeText
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfContentEditor. Membuat anotasi teks bebas dalam dokumen PDF
type: docs
weight: 160
url: /id/net/aspose.pdf.facades/pdfcontenteditor/createfreetext/
---
## Metode PdfContentEditor.CreateFreeText

Membuat anotasi teks bebas dalam dokumen PDF

```csharp
public void CreateFreeText(Rectangle rect, string contents, int page)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | Rectangle | Persegi panjang anotasi yang menentukan lokasi anotasi di halaman. |
| contents | String | Isi dari anotasi. |
| page | Int32 | Nomor halaman asli tempat anotasi teks akan dibuat. |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFreeText(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 1);
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)