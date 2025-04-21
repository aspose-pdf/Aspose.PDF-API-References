---
title: Delegate HtmlSaveOptions.ResourceSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Bu özelliğe, PDF'den çıkarılan ve PDF'den HTML'ye dönüştürme sırasında harici kaynak olarak kaydedilmesi gereken dış kaynak işleme uygulayan özel bir yöntemden oluşturulmuş bir delege atayabilirsiniz. Bu durumda, akışta veya diskte kaydetme gibi işlemler bu özel kodda yapılabilir ve bu özel kod, daha sonra oluşturulan HTML'ye dahil edilecek olan, o resim kaynağı için varsayılan yolun yerine geçecek bir yol döndürmelidir. Bu durumda, resmin kaydedilmesi için gerekli tüm işlemler sağlanan yöntemin kodunda gerçekleştirilmelidir, çünkü sonuçların dönüştürücü kodunda kaydedilmesi kullanılmayacaktır. Eğer bu veya o dosya için bir nedenle işlemenin dönüştürücünün kodu tarafından, özel kodda değil, yapılması gerekiyorsa, lütfen özel kodda 'resourceSavingInfo' parametre değişkeninin 'CustomProcessingCancelled' bayrağını ayarlayın. Bu, dönüştürücüye, o kaynağın işlenmesi için gerekli tüm adımların dönüştürücü içinde yapılması gerektiğini, sanki dış bir özel kod yokmuş gibi sinyal eder.
type: docs
weight: 5730
url: /tr/net/aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
## HtmlSaveOptions.ResourceSavingStrategy delegesi

Bu özelliğe, PDF'den çıkarılan ve PDF'den HTML'ye dönüştürme sırasında harici kaynak olarak kaydedilmesi gereken dış kaynak (Font veya Resim) işleme uygulayan özel bir yöntemden oluşturulmuş bir delege atayabilirsiniz. Bu durumda, akışta veya diskte kaydetme gibi işlemler bu özel kodda yapılabilir ve bu özel kod, daha sonra oluşturulan HTML'ye dahil edilecek olan, o resim kaynağı için varsayılan yolun yerine geçecek bir yol (veya tırnak işareti olmadan başka bir dize) döndürmelidir. Bu durumda, resmin kaydedilmesi için gerekli tüm işlemler sağlanan yöntemin kodunda gerçekleştirilmelidir, çünkü sonuçların dönüştürücü kodunda kaydedilmesi kullanılmayacaktır. Eğer bu veya o dosya için bir nedenle işlemenin dönüştürücünün kodu tarafından, özel kodda değil, yapılması gerekiyorsa, lütfen özel kodda 'resourceSavingInfo' parametre değişkeninin 'CustomProcessingCancelled' bayrağını ayarlayın. Bu, dönüştürücüye, o kaynağın işlenmesi için gerekli tüm adımların dönüştürücü içinde yapılması gerektiğini, sanki dış bir özel kod yokmuş gibi sinyal eder.

```csharp
public delegate string ResourceSavingStrategy(ResourceSavingInfo resourceSavingInfo);
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| resourceSavingInfo | ResourceSavingInfo | kaynağın kaydedilmesi için veri kümesini temsil eder |

### Dönüş Değeri

HTML oluşturma sırasında kullanılacak kaydedilen kaynağın URL'sini döndürmelidir.

### Ayrıca Bakınız

* sınıf [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* sınıf [HtmlSaveOptions](../htmlsaveoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)