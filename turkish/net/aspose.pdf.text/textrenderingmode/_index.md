---
title: Enum TextRenderingMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextRenderingMode enum. Metin renderleme modu Tmode, metin gösteriminin glif konturlarının çizilmesine, doldurulmasına, kesme sınırı olarak kullanılmasına veya bu üçünün bir kombinasyonuna neden olup olmayacağını belirler.
type: docs
weight: 11000
url: /tr/net/aspose.pdf.text/textrenderingmode/
---
## TextRenderingMode enumerasyonu

Metin renderleme modu, Tmode, metin gösteriminin glif konturlarının çizilmesine, doldurulmasına, kesme sınırı olarak kullanılmasına veya bu üçünün bir kombinasyonuna neden olup olmayacağını belirler.

```csharp
public enum TextRenderingMode
```

### Değerler

| İsim | Değer | Açıklama |
| --- | --- | --- |
| FillText | `0` | Metni doldur. |
| StrokeText | `1` | Metni çiz. |
| FillThenStrokeText | `2` | Önce doldur, sonra metni çiz. |
| Invisible | `3` | Ne doldur ne de metni çiz (görünmez). |
| FillTextAndAddPathToClipping | `4` | Metni doldur ve kesme için yola ekle (bkz. 9.3.6, "Metin Renderleme Modu,"). |
| StrokeTextAndAddPathToClipping | `5` | Metni çiz ve kesme için yola ekle. |
| FillThenStrokeTextAndAddPathToClipping | `6` | Önce doldur, sonra metni çiz ve kesme için yola ekle. |
| AddPathToClipping | `7` | Metni kesme için yola ekle. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)