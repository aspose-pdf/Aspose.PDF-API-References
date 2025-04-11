---
title: PdfContentEditor.DrawCurve
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodu. Eğri notasyonu oluşturur
type: docs
weight: 360
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/drawcurve/
---
## PdfContentEditor.DrawCurve metodu

Eğri notasyonu oluşturur.

```csharp
public void DrawCurve(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lineInfo | LineInfo | LineInfo sınıfının örneği. |
| page | Int32 | Notasyonun oluşturulacağı orijinal sayının numarası. |
| annotRect | Rectangle | Notasyonun sayfadaki konumunu tanımlayan notasyon dikdörtgeni. |
| annotContents | String | Notasyonun içeriği. |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
newApiEditor.BindPdf("example.pdf");
LineInfo lineInfo = new LineInfo();
lineInfo.VerticeCoordinate = new float[] { 0, 0, 100, 100 };  //x1, y1, x2, y2, .. xn, yn
lineInfo.Visibility = true;
editor.DrawCurve(lineInfo, 1, new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* sınıf [LineInfo](../../lineinfo/)
* sınıf [PdfContentEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)