---
title: PdfContentEditor.DrawCurve
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfContentEditor. Membuat anotasi kurva
type: docs
weight: 360
url: /id/net/aspose.pdf.facades/pdfcontenteditor/drawcurve/
---
## Metode PdfContentEditor.DrawCurve

Membuat anotasi kurva.

```csharp
public void DrawCurve(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lineInfo | LineInfo | Instansi dari kelas LineInfo. |
| page | Int32 | Nomor halaman asli tempat anotasi akan dibuat. |
| annotRect | Rectangle | Persegi panjang anotasi yang mendefinisikan lokasi anotasi di halaman. |
| annotContents | String | Isi dari anotasi. |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
newApiEditor.BindPdf("example.pdf");
LineInfo lineInfo = new LineInfo();
lineInfo.VerticeCoordinate = new float[] { 0, 0, 100, 100 };  //x1, y1, x2, y2, .. xn, yn
lineInfo.Visibility = true;
editor.DrawCurve(lineInfo, 1, new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [LineInfo](../../lineinfo/)
* kelas [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)