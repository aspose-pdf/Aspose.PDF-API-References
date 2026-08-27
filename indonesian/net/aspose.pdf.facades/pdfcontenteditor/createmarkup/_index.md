---
title: "PdfContentEditor.CreateMarkup"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfContentEditor. Membuat anotasi markup dalam dokumen PDF"
type: docs
weight: 200
url: /id/net/aspose.pdf.facades/pdfcontenteditor/createmarkup/
---
## PdfContentEditor.CreateMarkup method

Membuat anotasi markup dalam dokumen PDF.

```csharp
public void CreateMarkup(Rectangle rect, string contents, int type, int page, Color clr)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | Rectangle | Persegi panjang yang menentukan lokasi anotasi pada halaman. |
| isi | String | Isi anotasi. |
| type | Int32 | Tipe anotasi markup. Dapat berupa 0 (Highlight), 1 (Underline), 2 (StrikeOut), 3 (Squiggly). |
| halaman | Int32 | Jumlah halaman asli tempat anotasi akan dibuat. |
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

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


