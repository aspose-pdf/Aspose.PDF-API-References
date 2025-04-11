---
title: PdfContentEditor.CreateMarkup
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfContentEditor. Membuat anotasi markup di dokumen PDF
type: docs
weight: 200
url: /id/net/aspose.pdf.facades/pdfcontenteditor/createmarkup/
---
## Metode PdfContentEditor.CreateMarkup

Membuat anotasi markup di dokumen PDF.

```csharp
public void CreateMarkup(Rectangle rect, string contents, int type, int page, Color clr)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | Rectangle | Persegi panjang yang mendefinisikan lokasi anotasi di halaman. |
| contents | String | Isi dari anotasi. |
| type | Int32 | Tipe anotasi markup. Dapat berupa 0 (Sorot), 1 (Garis Bawah), 2 (Coret), 3 (Bergelombang). |
| page | Int32 | Nomor halaman asli tempat anotasi akan dibuat. |
| clr | Color | Warna markup. |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateMarkup(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", 0, 1, System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)