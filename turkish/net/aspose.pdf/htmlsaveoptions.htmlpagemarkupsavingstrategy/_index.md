---
title: Delegate HtmlSaveOptions.HtmlPageMarkupSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Dönüşüm sonucu bir veya birden fazla HTML sayfası içerebilir; bu sayfalar ayrıca resimler veya yazı tipleri gibi harici dosyalara da referans verebilir. Bu özelliğe, dönüşüm sırasında oluşturulan HTML sayfasının (HTML'nin kendisi) işlenmesini uygulayan özel bir yöntemden oluşturulan bir delege atayabilirsiniz. Bu durumda, akışta veya diskte kaydetme gibi işlemler bu özel kodda gerçekleştirilebilir. Bu durumda, HTML sayfasının işaretlemesini kaydetmek için gerekli tüm işlemler sağlanan yöntemin kodunda gerçekleştirilmelidir, çünkü sonuçların dönüştürücü kodunda kaydedilmesi kullanılmayacaktır. Eğer bu veya şu durum için bir nedenle işlemenin dönüştürücünün kodu tarafından, özel kodda değil, yapılması gerekiyorsa, lütfen özel kodda 'htmlSavingInfo' parametre değişkeninin 'CustomProcessingCancelled' bayrağını ayarlayın: bu, dönüştürücüye, o kaynağın işlenmesi için gerekli tüm adımların dönüştürücü içinde, dışarıda herhangi bir özel kaydetme kodu yokmuş gibi gerçekleştirilmesi gerektiğini bildirir.
type: docs
weight: 5680
url: /tr/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
## HtmlSaveOptions.HtmlPageMarkupSavingStrategy delegesi

Dönüşüm sonucu bir veya birden fazla HTML sayfası (bu sayfalar ayrıca resimler veya yazı tipleri gibi harici dosyalara da referans verebilir) içerebilir. Bu özelliğe, dönüşüm sırasında oluşturulan HTML sayfasının (HTML'nin kendisi) işlenmesini uygulayan özel bir yöntemden oluşturulan bir delege atayabilirsiniz. Bu durumda, akışta veya diskte kaydetme gibi işlemler bu özel kodda gerçekleştirilebilir. Bu durumda, HTML sayfasının işaretlemesini kaydetmek için gerekli tüm işlemler sağlanan yöntemin kodunda gerçekleştirilmelidir, çünkü sonuçların dönüştürücü kodunda kaydedilmesi kullanılmayacaktır. Eğer bu veya şu durum için bir nedenle işlemenin dönüştürücünün kodu tarafından, özel kodda değil, yapılması gerekiyorsa, lütfen özel kodda 'htmlSavingInfo' parametre değişkeninin 'CustomProcessingCancelled' bayrağını ayarlayın: bu, dönüştürücüye, o kaynağın işlenmesi için gerekli tüm adımların dönüştürücü içinde, dışarıda herhangi bir özel kaydetme kodu yokmuş gibi gerçekleştirilmesi gerektiğini bildirir.

```csharp
public delegate void HtmlPageMarkupSavingStrategy(HtmlPageMarkupSavingInfo htmlSavingInfo);
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlSavingInfo | HtmlPageMarkupSavingInfo | sağlanan HTML sayfasının kaydedilmesi veya işlenmesi için kullanılabilecek verileri temsil eder |

### Ayrıca Bakınız

* sınıf [HtmlPageMarkupSavingInfo](../htmlsaveoptions.htmlpagemarkupsavinginfo/)
* sınıf [HtmlSaveOptions](../htmlsaveoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)