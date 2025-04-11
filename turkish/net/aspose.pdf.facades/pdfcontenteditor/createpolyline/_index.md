---
title: PdfContentEditor.CreatePolyLine
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodu. Poligon anotasyonu oluşturur
type: docs
weight: 240
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/createpolyline/
---
## PdfContentEditor.CreatePolyLine metodu

Poligon anotasyonu oluşturur.

```csharp
public void CreatePolyLine(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lineInfo | LineInfo | LineInfo sınıfının örneği. |
| page | Int32 | Anotasyonun oluşturulacağı orijinal sayının numarası. |
| annotRect | Rectangle | Anotasyonun sayfadaki konumunu tanımlayan anotasyon dikdörtgeni. |
| annotContents | String | Anotasyonun içeriği. |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
LineInfo lineInfo = new LineInfo();
lineInfo.VerticeCoordinate = new float[] { 0, 0, 100, 100, 100, 50 };
lineInfo.Visibility = true;
editor.CreatePolyLine(lineInfo, 1 , new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* sınıf [LineInfo](../../lineinfo/)
* sınıf [PdfContentEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)