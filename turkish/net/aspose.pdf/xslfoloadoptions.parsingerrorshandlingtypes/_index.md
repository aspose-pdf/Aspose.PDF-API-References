---
title: Enum XslFoLoadOptions.ParsingErrorsHandlingTypes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XslFoLoadOptionsParsingErrorsHandlingTypes enum. Kaynak XSLFO belgesi biçimlendirme hataları içerebilir. Bu enum, bu tür biçimlendirme hatalarının işlenmesi için olası stratejileri sıralar.
type: docs
weight: 11540
url: /tr/net/aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
## XslFoLoadOptions.ParsingErrorsHandlingTypes enumerasyonu

Kaynak XSLFO belgesi biçimlendirme hataları içerebilir. Bu enum, bu tür biçimlendirme hatalarının işlenmesi için olası stratejileri sıralar.

```csharp
public enum ParsingErrorsHandlingTypes
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| TryIgnore | `0` | Bu durumda dönüştürücüye dönüştürmeye devam etmesi ve bulunan biçimlendirme hatalarını göz ardı etmesi talimatı verilecektir. Bu durumda başarı garanti edilmez, dönüştürücüde daha sonra ciddi sorunlar ortaya çıkabilir ve böyle bir durumda bulunan biçimlendirme hatalarının listesi ile bir istisna fırlatılacaktır. |
| ThrowExceptionImmediately | `1` | Bu durumda dönüşüm hemen durdurulacak ve ilk biçimlendirme hatası tespit edildikten hemen sonra bir istisna fırlatılacaktır. |
| InvokeCustomHandler | `2` | Bu en esnek yöntemdir - özel kod, biçimlendirme hatası tespit edildiğinde çağrılacak özel bir işleyici sağlamalıdır (WarningCallback özelliğinde). O işleyici, örneğin hataları kaydedebilir veya sayabilir ve bu veya şu hata için işlemenin devam edip edemeyeceğine dair bir karar verecektir. |

### Ayrıca Bakınız

* sınıf [XslFoLoadOptions](../xslfoloadoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)