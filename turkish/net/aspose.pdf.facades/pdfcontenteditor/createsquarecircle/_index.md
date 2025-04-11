---
title: PdfContentEditor.CreateSquareCircle
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodu. Kare daire notasyonu oluşturur
type: docs
weight: 280
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/createsquarecircle/
---
## PdfContentEditor.CreateSquareCircle metodu

Kare-daire notasyonu oluşturur.

```csharp
public void CreateSquareCircle(Rectangle rect, string contents, Color clr, bool square, int page, 
    int borderWidth)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | Dikdörtgen | Notasyonun sayfadaki konumunu tanımlayan notasyon dikdörtgeni. |
| contents | Dize | Notasyonun içeriği. |
| clr | Renk | Kare veya dairenin rengi. |
| square | Boolean | Doğru (kare), yanlış (daire). |
| page | Int32 | Notasyonun oluşturulacağı orijinal sayının numarası. |
| borderWidth | Int32 | Kare veya dairenin kenar genişliği. |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateSquareCircle(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, false, 1, 5);
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfContentEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)