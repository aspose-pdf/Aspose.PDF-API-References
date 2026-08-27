---
title: "PdfContentEditor.CreateCaret"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfContentEditor. Membuat anotasi caret"
type: docs
weight: 130
url: /id/net/aspose.pdf.facades/pdfcontenteditor/createcaret/
---
## PdfContentEditor.CreateCaret method

Membuat anotasi caret.

```csharp
public void CreateCaret(int page, Rectangle annotRect, Rectangle caretRect, string symbol, 
    string annotContents, Color color)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| halaman | Int32 | Jumlah halaman asli tempat anotasi akan dibuat. |
| annotRect | Rectangle | Persegi panjang anotasi yang menentukan lokasi anotasi pada halaman. |
| caretRect | Rectangle | Batas sebenarnya dari caret yang mendasari. |
| symbol | String | Sebuah simbol akan dikaitkan dengan caret. Nilainya dapat berupa: "P" (Paragraf), "None". |
| annotContents | String | Isi anotasi. |
| color | Color | Warna anotasi. |

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

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


