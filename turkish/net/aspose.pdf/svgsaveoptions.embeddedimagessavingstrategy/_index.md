---
title: Delegate SvgSaveOptions.EmbeddedImagesSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Bu türdeki bir özelliğe, PDF'den oluşturulan SVG'den çıkarılan görüntünün dışa aktarımını işleyen özel bir yöntemden oluşturulan delegeleri atayabilirsiniz ve bu, PDF'den HTML'ye dönüştürme sırasında dış kaynak olarak kaydedilmelidir. Bu durumda, akışa veya diske kendi başına kaydetme gibi işlemler bu özel kodda yapılabilir ve bu özel kod, daha sonra o görüntü kaynağına ait orijinal varsayılan yolun yerine oluşturulan SVG'ye dahil edilecek bir yol döndürmelidir. Bu durumda, görüntünün kaydedilmesi için gerekli tüm işlemler sağlanan yöntemin kodunda gerçekleştirilmelidir, çünkü dönüştürücünün kodunda sonucun kaydedilmesi kullanılmayacaktır. Eğer bu veya şu dosya için bir nedenle işlemenin dönüştürücünün kodu tarafından, özel kodda değil, yapılması gerekiyorsa, lütfen özel kodda 'imageSavingInfo' parametre değişkeninin 'CustomProcessingCancelled' bayrağını ayarlayın. Bu, dönüştürücüye, o kaynağın işlenmesi için gerekli tüm adımların dönüştürücü içinde yapılması gerektiğini, sanki dış bir özel kod yokmuş gibi sinyal eder. Kaydedilen görüntü hakkında bilgi temsil eder, özel kodda kullanılabilir, SVG'ye konulacak görüntünün URL'sini temsil eden bir dize döndürmelidir.
type: docs
weight: 10240
url: /tr/net/aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
## SvgSaveOptions.EmbeddedImagesSavingStrategy delegesi

Bu türdeki bir özelliğe, PDF'den oluşturulan SVG'den çıkarılan görüntünün dışa aktarımını işleyen özel bir yöntemden oluşturulan delegeleri atayabilirsiniz ve bu, PDF'den HTML'ye dönüştürme sırasında dış kaynak olarak kaydedilmelidir. Bu durumda, akışa veya diske kendi başına kaydetme gibi işlemler bu özel kodda yapılabilir ve bu özel kod, daha sonra o görüntü kaynağına ait orijinal varsayılan yolun yerine oluşturulan SVG'ye dahil edilecek bir yol (veya herhangi başka bir tırnak işareti olmadan bir dize) döndürmelidir. Bu durumda, görüntünün kaydedilmesi için gerekli tüm işlemler sağlanan yöntemin kodunda gerçekleştirilmelidir, çünkü dönüştürücünün kodunda sonucun kaydedilmesi kullanılmayacaktır. Eğer bu veya şu dosya için bir nedenle işlemenin dönüştürücünün kodu tarafından, özel kodda değil, yapılması gerekiyorsa, lütfen özel kodda 'imageSavingInfo' parametre değişkeninin 'CustomProcessingCancelled' bayrağını ayarlayın. Bu, dönüştürücüye, o kaynağın işlenmesi için gerekli tüm adımların dönüştürücü içinde yapılması gerektiğini, sanki dış bir özel kod yokmuş gibi sinyal eder. Kaydedilen görüntü hakkında bilgi temsil eder, özel kodda kullanılabilir, SVG'ye konulacak görüntünün URL'sini temsil eden bir dize döndürmelidir.

```csharp
public delegate string EmbeddedImagesSavingStrategy(SvgImageSavingInfo imageSavingInfo);
```

### Ayrıca Bakınız

* sınıf [SvgImageSavingInfo](../svgsaveoptions.svgimagesavinginfo/)
* sınıf [SvgSaveOptions](../svgsaveoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)