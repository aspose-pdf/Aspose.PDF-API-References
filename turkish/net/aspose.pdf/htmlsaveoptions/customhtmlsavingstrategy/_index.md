---
title: HtmlSaveOptions.CustomHtmlSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: HtmlSaveOptions alanı. Dönüşüm sonucu bir veya birden fazla HTML sayfası içerebilir. Bu özelliğe, dönüşüm sırasında oluşturulan bir HTML sayfasının işlenmesini uygulayan özel bir yöntemden oluşturulan bir delege atayabilirsiniz (doğru bir şekilde - markup-HTML, varsa dış bağlantılı dosyalar olmadan). Bu durumda, işleme (örneğin, sayfanın HTML'sinin akışta veya diskte kaydedilmesi gibi) o özel kodda yapılabilir. Bu durumda, HTML sayfasının kaydedilmesi için gerekli tüm işlemler sağlanan yöntemin kodunda gerçekleştirilmelidir, çünkü sonuçların dönüştürücü kodunda kaydedilmesi kullanılmayacaktır. Eğer bu veya başka bir durum için bir nedenle işleme dönüştürücünün kodu tarafından, özel kodda değil, yapılması gerekiyorsa, lütfen özel kodda 'htmlSavingInfo' parametre değişkeninin 'CustomProcessingCancelled' bayrağını ayarlayın: bu, dönüştürücüye o kaynağın işlenmesi için gerekli tüm adımların dönüştürücü içinde, dış bir özel kod olmaksızın yapılması gerektiğini sinyal edecektir.
type: docs
weight: 270
url: /tr/net/aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/
---
## HtmlSaveOptions.CustomHtmlSavingStrategy alanı

Dönüşüm sonucu bir veya birden fazla HTML sayfası içerebilir. Bu özelliğe, dönüşüm sırasında oluşturulan bir HTML sayfasının işlenmesini uygulayan özel bir yöntemden oluşturulan bir delege atayabilirsiniz (doğru bir şekilde - markup-HTML, varsa dış bağlantılı dosyalar olmadan). Bu durumda, işleme (örneğin, sayfanın HTML'sinin akışta veya diskte kaydedilmesi gibi) o özel kodda yapılabilir. Bu durumda, HTML sayfasının kaydedilmesi için gerekli tüm işlemler sağlanan yöntemin kodunda gerçekleştirilmelidir, çünkü sonuçların dönüştürücü kodunda kaydedilmesi kullanılmayacaktır. Eğer bu veya başka bir durum için bir nedenle işleme dönüştürücünün kodu tarafından, özel kodda değil, yapılması gerekiyorsa, lütfen özel kodda 'htmlSavingInfo' parametre değişkeninin 'CustomProcessingCancelled' bayrağını ayarlayın: bu, dönüştürücüye o kaynağın işlenmesi için gerekli tüm adımların dönüştürücü içinde, dış bir özel kod olmaksızın yapılması gerektiğini sinyal edecektir.

```csharp
public HtmlPageMarkupSavingStrategy CustomHtmlSavingStrategy;
```

### Ayrıca Bakınız

* delege [HtmlPageMarkupSavingStrategy](../../htmlsaveoptions.htmlpagemarkupsavingstrategy/)
* sınıf [HtmlSaveOptions](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)