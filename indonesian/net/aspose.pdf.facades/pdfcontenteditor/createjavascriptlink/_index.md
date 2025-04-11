---
title: PdfContentEditor.CreateJavaScriptLink
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfContentEditor. Membuat tautan ke JavaScript dalam dokumen PDF
type: docs
weight: 170
url: /id/net/aspose.pdf.facades/pdfcontenteditor/createjavascriptlink/
---
## Metode PdfContentEditor.CreateJavaScriptLink

Membuat tautan ke JavaScript dalam dokumen PDF.

```csharp
public void CreateJavaScriptLink(string code, Rectangle rect, int originalPage, Color color)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| code | String | Kode JavaScript. |
| rect | Rectangle | Persegi panjang untuk klik aktif. |
| originalPage | Int32 | Nomor halaman asli di mana persegi panjang yang terikat dengan tautan akan dibuat. |
| color | Color | Warna persegi panjang untuk klik aktif. |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateJavaScriptLink("app.alert('welcome to aspose!');",
    new System.Drawing.Rectangle(0, 0, 100, 100), 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)