---
title: PdfContentEditor.CreatePolygon
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodu. Çokgen notasyonu oluşturur
type: docs
weight: 230
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/createpolygon/
---
## PdfContentEditor.CreatePolygon metodu

Çokgen notasyonu oluşturur.

```csharp
public void CreatePolygon(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
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
editor.BindPdf("example.pdf");
LineInfo lineInfo = new LineInfo();
lineInfo.VerticeCoordinate = new float[] { 0, 0, 100, 100, 100, 50 };
lineInfo.Visibility = true;
editor.CreatePolygon(lineInfo, 1 , new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* sınıf [LineInfo](../../lineinfo/)
* sınıf [PdfContentEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)