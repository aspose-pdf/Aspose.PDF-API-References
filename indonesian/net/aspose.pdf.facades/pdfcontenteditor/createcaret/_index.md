---
title: PdfContentEditor.CreateCaret
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfContentEditor. Membuat anotasi caret
type: docs
weight: 130
url: /id/net/aspose.pdf.facades/pdfcontenteditor/createcaret/
---
## Metode PdfContentEditor.CreateCaret

Membuat anotasi caret.

```csharp
public void CreateCaret(int page, Rectangle annotRect, Rectangle caretRect, string symbol, 
    string annotContents, Color color)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| page | Int32 | Nomor halaman asli tempat anotasi akan dibuat. |
| annotRect | Rectangle | Persegi panjang anotasi yang mendefinisikan lokasi anotasi di halaman. |
| caretRect | Rectangle | Batasan aktual dari caret yang mendasarinya. |
| symbol | String | Simbol yang akan diasosiasikan dengan caret. Nilai dapat berupa: "P" (Paragraf), "None". |
| annotContents | String | Isi dari anotasi. |
| color | Color | Warna dari anotasi. |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateCaret(1,
    new System.Drawing.Rectangle(50, 50, 100, 100),
    new System.Drawing.Rectangle(60, 60, 70, 70),
    "None", "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)