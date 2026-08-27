---
title: "PdfContentEditor.DrawCurve"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfContentEditor. Membuat anotasi kurva"
type: docs
weight: 360
url: /id/net/aspose.pdf.facades/pdfcontenteditor/drawcurve/
---
## PdfContentEditor.DrawCurve method

Membuat anotasi kurva.

```csharp
public void DrawCurve(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lineInfo | LineInfo | Instansi kelas LineInfo. |
| halaman | Int32 | Jumlah halaman asli tempat anotasi akan dibuat. |
| annotRect | Rectangle | Persegi panjang anotasi yang menentukan lokasi anotasi pada halaman. |
| annotContents | String | Isi anotasi. |

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

* class [LineInfo](../../lineinfo/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


