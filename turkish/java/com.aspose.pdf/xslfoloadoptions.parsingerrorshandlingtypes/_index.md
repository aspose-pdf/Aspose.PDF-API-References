---
title: "XslFoLoadOptions.ParsingErrorsHandlingTypes"
linktitle: "XslFoLoadOptions.ParsingErrorsHandlingTypes"
second_title: "Aspose.PDF for Java API Referansı"
description: "Kaynak XSLFO belgesi biçimlendirme hataları içerebilir. Bu enum, bu tür biçimlendirme hatalarını ele almanın olası stratejilerini listeler."
type: docs
weight: 5790
url: /tr/java/com.aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes, com.aspose.ms.System.Enum, com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes

```
public static final class XslFoLoadOptions.ParsingErrorsHandlingTypes extends com.aspose.ms.System.Enum
```

Kaynak XSLFO belgesi biçimlendirme hataları içerebilir. Bu enum, bu tür biçimlendirme hatalarını ele almanın olası stratejilerini listeler.

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [InvokeCustomHandler](#InvokeCustomHandler) | Bu, en çevik yöntemdir - özel kod, (WarningCallback özelliğinde) biçimlendirme hatası tespit edildiğinde çağrılacak özel bir işleyici sağlamalıdır. Bu işleyici, örn. hataları kaydedebilir veya sayabilir vb. ve işleme bu ya da o hata için devam edilip edilemeyeceğine karar verir. |
| [ThrowExceptionImmediately](#ThrowExceptionImmediately) | Bu durumda dönüşüm hemen durdurulacak ve ilk biçimlendirme hatası tespit edildikten hemen sonra bir istisna fırlatılacaktır. |
| [TryIgnore](#TryIgnore) | Bu durumda dönüştürücü, dönüşüme devam etmeye çalışması ve bulunan biçimlendirme hatalarını yok sayması talimatını alır. Bu durumda başarı garantilenmez, dönüştürücüde daha sonra ciddi sorunlar ortaya çıkabilir ve bu gibi bir durumda bulunan biçimlendirme hatalarının listesiyle bir istisna fırlatılır. |

### InvokeCustomHandler {#InvokeCustomHandler}
```
public static final int InvokeCustomHandler
```

Bu, en çevik yöntemdir - özel kod, (WarningCallback özelliğinde) biçimlendirme hatası tespit edildiğinde çağrılacak özel bir işleyici sağlamalıdır. Bu işleyici, örn. hataları kaydedebilir veya sayabilir vb. ve işleme bu ya da o hata için devam edilip edilemeyeceğine karar verir.

### ThrowExceptionImmediately {#ThrowExceptionImmediately}
```
public static final int ThrowExceptionImmediately
```

Bu durumda dönüşüm hemen durdurulacak ve ilk biçimlendirme hatası tespit edildikten hemen sonra bir istisna fırlatılacaktır.

### TryIgnore {#TryIgnore}
```
public static final int TryIgnore
```

Bu durumda dönüştürücü, dönüşüme devam etmeye çalışması ve bulunan biçimlendirme hatalarını yok sayması talimatını alır. Bu durumda başarı garantilenmez, dönüştürücüde daha sonra ciddi sorunlar ortaya çıkabilir ve bu gibi bir durumda bulunan biçimlendirme hatalarının listesiyle bir istisna fırlatılır.
