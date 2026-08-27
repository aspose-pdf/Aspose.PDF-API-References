---
title: "PdfContentEditor.CreatePolyLine"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfContentEditor. Membuat anotasi polyline"
type: docs
weight: 240
url: /id/net/aspose.pdf.facades/pdfcontenteditor/createpolyline/
---
## PdfContentEditor.CreatePolyLine method

Membuat anotasi polyline.

```csharp
public void CreatePolyLine(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
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
editor.BindPdf("example.pdf");
LineInfo lineInfo = new LineInfo();
lineInfo.VerticeCoordinate = new float[] { 0, 0, 100, 100, 100, 50 };
lineInfo.Visibility = true;
editor.CreatePolyLine(lineInfo, 1 , new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### Lihat Juga

* class [LineInfo](../../lineinfo/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


