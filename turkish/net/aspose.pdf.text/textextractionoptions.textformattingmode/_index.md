---
title: Enum TextExtractionOptions.TextFormattingMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextExtractionOptionsTextFormattingMode enum. PDF belgesini metne dönüştürürken kullanılabilecek farklı modları tanımlar. TextDevice sınıfına bakın.
type: docs
weight: 10900
url: /tr/net/aspose.pdf.text/textextractionoptions.textformattingmode/
---
## TextExtractionOptions.TextFormattingMode enumerasyonu

PDF belgesini metne dönüştürürken kullanılabilecek farklı modları tanımlar. !:TextDevice sınıfına bakın.

```csharp
public enum TextFormattingMode
```

### Değerler

| İsim | Değer | Açıklama |
| --- | --- | --- |
| Pure | `0` | PDF içeriğini biraz biçimlendirme rutinleri ile temsil eder. |
| Raw | `1` | PDF içeriğini olduğu gibi, yani biçimlendirme olmadan temsil eder. |
| Flatten | `2` | PDF içeriğini metin parçalarını koordinatlarına göre konumlandırarak temsil eder. Temelde "Raw" moduna benzer. Ancak "Raw", bir belgedeki metin parçalarının (operatörlerin) yapısını korumaya odaklanırken, "Flatten" metni okunduğu sırayla tutmaya odaklanır. |
| MemorySaving | `3` | Bellek tasarrufu ile çıkarım. 'Raw' moduna neredeyse aynıdır ama biraz daha hızlı çalışır ve daha az bellek kullanır. |

### Ayrıca Bakınız

* sınıf [TextExtractionOptions](../textextractionoptions/)
* ad alanı [Aspose.Pdf.Text](../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../)