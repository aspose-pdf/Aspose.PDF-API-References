---
title: "PdfContentEditor.CreatePolygon"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "metode PdfContentEditor. Membuat anotasi poligon"
type: docs
weight: 230
url: /id/net/aspose.pdf.facades/pdfcontenteditor/createpolygon/
---
## PdfContentEditor.CreatePolygon method

Membuat anotasi poligon.

```csharp
public void CreatePolygon(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
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
editor.CreatePolygon(lineInfo, 1 , new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### Lihat Juga

* class [LineInfo](../../lineinfo/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


