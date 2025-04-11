---
title: Class LoadOptions.ResourceLoadingResult
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LoadOptionsResourceLoadingResult sınıfı. Kaynağın özel yüklenme sonucu
type: docs
weight: 6150
url: /tr/net/aspose.pdf/loadoptions.resourceloadingresult/
---
## LoadOptions.ResourceLoadingResult sınıfı

Kaynağın özel yüklenme sonucu

```csharp
public class ResourceLoadingResult
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [ResourceLoadingResult](../../aspose.pdf/loadoptions.resourceloadingresult/.ctor)(byte[]) | Yükleme sonucunun örneğini oluşturur |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Data](../../aspose.pdf/loadoptions.resourceloadingresult/data) { get; } | Özel yükleyici ile yüklenen ikili veri - yüklemeden sonra ayarlanmalıdır |

## Alanlar

| İsim | Açıklama |
| --- | --- |
| [EncodingIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/encodingifknown) | Bazen kaynağın kodlaması yükleme sırasında veya sonrasında bilinir. Bu durumda özel kod, bu parametre aracılığıyla dönüştürücüye bu bilgiyi sağlayabilir. Kodlama bilinmiyorsa veya önemli değilse bu parametreyi null bırakabilirsiniz. |
| [ExceptionOfLoadingIfAny](../../aspose.pdf/loadoptions.resourceloadingresult/exceptionofloadingifany) | Bazen istenen kaynağı bir nedenle yüklemek imkansızdır. Kaynağın mevcut olmaması genellikle dönüşümün çökmesine neden olmaz ve sonuç belgesi yine de oluşturulabilir (ancak belki biraz daha kötü kalitede, resim olmadan vb.). Yükleme sırasında bir istisna oluşursa, sadece onu yakalayın ve bu parametreye koyun - bazen bu bilgi, sonucun işlenmesi için dönüştürücü için faydalıdır. |
| [LoadingCancelled](../../aspose.pdf/loadoptions.resourceloadingresult/loadingcancelled) | Bazen bazı nedenlerden dolayı yükleme özel kod tarafından gerçekleşmemelidir. Bu durumda lütfen bu bayrağı True olarak ayarlayın. Bu durumda dönüştürücü, o sonucu elde etmek için dahili varsayılan kaynak yükleyicisini kullanmaya çalışacaktır (özel strateji sağlanmadığında nasıl davrandığı gibi). |
| [MIMETypeIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/mimetypeifknown) | Bazen yüklenen kaynağın MIME türü hakkında bilgi, dönüştürücü için faydalıdır. Bu parametreye MIME türünü (yüklemeden sonra biliniyorsa) sağlayabilirsiniz. MIME türü bilinmiyorsa veya sağlanması gerekmiyorsa parametreyi null bırakın. |

### Ayrıca Bakınız

* sınıf [LoadOptions](../loadoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)