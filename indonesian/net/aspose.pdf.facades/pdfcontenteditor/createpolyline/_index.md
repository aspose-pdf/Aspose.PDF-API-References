---
title: PdfContentEditor.CreatePolyLine
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfContentEditor. Membuat anotasi poligon
type: docs
weight: 240
url: /id/net/aspose.pdf.facades/pdfcontenteditor/createpolyline/
---
## Metode PdfContentEditor.CreatePolyLine

Membuat anotasi poligon.

```csharp
public void CreatePolyLine(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
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
editor.BindPdf("example.pdf");
LineInfo lineInfo = new LineInfo();
lineInfo.VerticeCoordinate = new float[] { 0, 0, 100, 100, 100, 50 };
lineInfo.Visibility = true;
editor.CreatePolyLine(lineInfo, 1 , new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [LineInfo](../../lineinfo/)
* kelas [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)