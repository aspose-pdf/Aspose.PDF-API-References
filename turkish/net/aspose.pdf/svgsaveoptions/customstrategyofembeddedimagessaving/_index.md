---
title: SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving
second_title: Aspose.PDF for .NET API Reference
description: SvgSaveOptions alanı. Bu alan, kaydedilen SVG'ye gömülü BMP veya JPEG gibi oluşturulan referans dış görüntü dosyalarının özelleştirilmiş işlenmesi için dönüşüm sırasında kullanılacak kaydetme stratejisini içerebilir. Bu strateji, kaynakları işlemesi ve üretilen SVG'deki kaydedilen kaynağın istenen URI'sini temsil eden bir dize döndürmesi gerekir. Bu veya şu dosya için işleme, bir nedenle dönüştürücünün kodu tarafından, özel kodda değil, yapılması gerekiyorsa, lütfen özel kodda 'imageSavingInfo' parametre değişkeninin 'CustomProcessingCancelled' bayrağını ayarlayın. Bu, dönüştürücüye, o kaynağın işlenmesi için gerekli tüm adımların dönüştürücü içinde yapılması gerektiğini, sanki dış bir özel kod yokmuş gibi sinyal eder.
type: docs
weight: 30
url: /tr/net/aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/
---
## SvgSaveOptions.GömülüGörüntülerinKaydedilmesiİçinÖzelStrateji alanı

Bu alan, kaydedilen SVG'ye gömülü BMP veya JPEG gibi oluşturulan referans dış görüntü dosyalarının özelleştirilmiş işlenmesi için dönüşüm sırasında kullanılacak kaydetme stratejisini içerebilir. Bu strateji, kaynakları işlemesi ve üretilen SVG'deki kaydedilen kaynağın istenen URI'sini temsil eden bir dize döndürmesi gerekir. Bu veya şu dosya için işleme, bir nedenle dönüştürücünün kodu tarafından, özel kodda değil, yapılması gerekiyorsa, lütfen özel kodda 'imageSavingInfo' parametre değişkeninin 'CustomProcessingCancelled' bayrağını ayarlayın. Bu, dönüştürücüye, o kaynağın işlenmesi için gerekli tüm adımların dönüştürücü içinde yapılması gerektiğini, sanki dış bir özel kod yokmuş gibi sinyal eder.

```csharp
public EmbeddedImagesSavingStrategy CustomStrategyOfEmbeddedImagesSaving;
```

### Ayrıca Bakınız

* delegate [GömülüGörüntülerinKaydedilmesiStratejisi](../../svgsaveoptions.embeddedimagessavingstrategy/)
* class [SvgSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)