---
title: LoadOptions.ResourceLoadingResult
second_title: Aspose.PDF for .NET API Referansı
description: resource özel yüklemesinin sonucu
type: docs
weight: 3980
url: /tr/net/aspose.pdf/loadoptions.resourceloadingresult/
---
## LoadOptions.ResourceLoadingResult class

resource özel yüklemesinin sonucu

```csharp
public class ResourceLoadingResult
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ResourceLoadingResult](resourceloadingresult)(byte[]) | Sonuç yükleme örneğini oluşturur |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Data](../../aspose.pdf/resourceloadingresult/data) { get; } | Özel yükleyici ile yüklenen ikili veriler - yüklendikten sonra ayarlanmalıdır |

## Alanlar

| İsim | Tanım |
| --- | --- |
| [EncodingIfKnown](../../aspose.pdf/resourceloadingresult/encodingifknown) | Bazen kaynağın kodlaması yüklemeden sonra veya yükleme sırasında bilinir. Bu durumda özel kod, dönüştürücüye bu bilgiyi bu parametre aracılığıyla sağlayabilir. Kodlama bilinmiyorsa veya önemli değilse bu parametrede boş bırakabilirsiniz. |
| [ExceptionOfLoadingIfAny](../../aspose.pdf/resourceloadingresult/exceptionofloadingifany) | Bazen herhangi bir nedenle istenen kaynağı yüklemek imkansızdır. Kaynağın bulunmaması çoğu zaman dönüştürmenin çökmesine yol açmaz ve sonuç belgesi yine de oluşturulabilir (ama belki biraz daha kötü kalitede, resimler olmadan vb.). İstisna oluşursa yükleme sırasında, sadece onu yakalayın ve bu parametreyi girin - bazen bu bilgi dönüştürücü için sonucun oluşturulması için yararlıdır. |
| [LoadingCancelled](../../aspose.pdf/resourceloadingresult/loadingcancelled) | Bazen bazı nedenlerden dolayı yükleme özel kod oluşmamalıdır. Böyle bir durumda lütfen bu bayrağı True olarak ayarlayın. Böyle bir durumda dönüştürücü, bu sonucu elde etmek için dahili default kaynak yükleyiciyi kullanmayı deneyecektir (özel strateji sağlanmadığında olduğu gibi). |
| [MIMETypeIfKnown](../../aspose.pdf/resourceloadingresult/mimetypeifknown) | Bazen yüklenen kaynağın MIME türü hakkında bilgi dönüştürücü için yararlıdır Bu parametrede MIME türünü (yüklendikten sonra biliniyorsa) sağlayabilirsiniz. Please MIME türü bilinmediğinde veya bunu sağlamak gerekli olmadığında parametreyi null değerine eşit bırakın. |

### Ayrıca bakınız

* class [LoadOptions](../loadoptions)
* ad alanı [Aspose.Pdf](../../aspose.pdf)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->