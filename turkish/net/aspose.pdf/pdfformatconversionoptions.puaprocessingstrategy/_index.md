---
title: Enum PdfFormatConversionOptions.PuaProcessingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfFormatConversionOptionsPuaProcessingStrategy enum. Bazı PDF belgeleri, Özel Kullanım Alanı (PUA) ile ilgili özel unicode sembollerine sahiptir, açıklama için bkz. https//en.wikipedia.org/wiki/Private_Use_Areas. Bu semboller, "Metin Unicode Özel Kullanım Alanına eşlenmiştir ancak ActualText girişi mevcut değildir" gibi PDF/A uyumlu hatalara neden olur. Bu enumeration, PUA sembollerini işlemek için kullanılabilecek stratejileri tanımlar.
type: docs
weight: 8390
url: /tr/net/aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
## PdfFormatConversionOptions.PuaProcessingStrategy enumeration

Bazı PDF belgeleri, Özel Kullanım Alanı (PUA) ile ilgili özel unicode sembollerine sahiptir, açıklama için bkz. https://en.wikipedia.org/wiki/Private_Use_Areas. Bu semboller, "Metin Unicode Özel Kullanım Alanına eşlenmiştir ancak ActualText girişi mevcut değildir" gibi PDF/A uyumlu hatalara neden olur. Bu enumeration, PUA sembollerini işlemek için kullanılabilecek stratejileri tanımlar.

```csharp
public enum PuaProcessingStrategy
```

### Değerler

| İsim | Değer | Açıklama |
| --- | --- | --- |
| None | `0` | PUA sembol işleme devre dışı bırakılır. Bu strateji, Level B uyumuna sahip PDF/A belgeleri için varsayılan olarak kullanılır. |
| SurroundPuaTextWithEmptyActualText | `1` | Boş metin içeren ActualText girişi ile işaretli içerik bloğu ekler. Bu strateji, işaretli içerik blokları olmayan belgeler için iyi sonuçlar verir. Level A uyumuna sahip PDF/A belgeleri için varsayılan olarak kullanılır. |
| SubstitutePuaSymbols | `2` | Bu strateji, 'SurroundPuaTextWithEmptyActualText' ile karşılaştırıldığında daha yavaş çalışır, ancak SurroundPuaTextWithEmptyActualText ile düzgün bir şekilde işlenemeyen belgeler için PUA uyumlu hataları kaldırabilir. PUA sembolleri, sembol 'boşluk' veya özel unicode ile değiştirilir (bazı PUA sembollerinin unicode karşılıkları vardır). Değiştirme, belgenin metnine değil, fontun iç verilerine ToUnicode'ya uygulanır, bu nedenle sembolün görünümünü etkilemez, ancak sembolün kopyala/yapıştır işlem sistemi tamponundaki sunumunu etkiler. |

### Ayrıca Bakınız

* class [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)