---
title: HtmlSaveOptions.CustomStrategyOfCssUrlCreation
second_title: Aspose.PDF for .NET API Reference
description: HtmlSaveOptions alanı. Bu alan, çok sayfalı oluşturma etkinse URL veya URL şablonu döndüren özel bir yöntem içerebilir. Aşağıda, oluşturulan sonuç HTML'sinde yer alması gereken konu CSS'sinin ayrıntılarına bakın. Örneğin, dönüştürücünün oluşturulan CSS'ye standart CSS dosya adı yerine belirli bir URL koymasını istiyorsanız, arzu edilen URL'yi üreten bir yöntem oluşturmalı ve bu özelliğe koymalısınız. SplitCssIntoPages bayrağı ayarlandığında, bu özel strateji varsa, CSS'nin tam URL'sini değil, daha çok yer tutucunun sayfa numarasıyla değiştirilmesiyle, dönüştürücü içinde string.Format işlevi kullanılarak bu veya o sayfaların CSS URL'sine çözülebilecek bir şablon dizesi döndürmelidir.
type: docs
weight: 300
url: /tr/net/aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/
---
## HtmlSaveOptions.CustomStrategyOfCssUrlCreation field

HtmlSaveOptions alanı. Bu alan, çok sayfalı üretim açık olduğunda URL veya URL şablonu döndüren özel bir yöntem içerebilir. Aşağıda, üretilen sonuç HTML'sinde yer alması gereken konu CSS'sinin detayları verilmiştir. Örneğin, dönüştürücünün üretilen CSS'ye standart CSS dosya adı yerine belirli bir URL koymasını istiyorsanız, o zaman sadece istenen URL'yi üreten bir yöntem oluşturmalı ve bu özelliğe koymalısınız. 'SplitCssIntoPages' bayrağı ayarlandığında, bu özel strateji (varsa) CSS'nin tam URL'sini değil, daha çok yer tutucunun sayfa numarası ile değiştirilmesinden sonra dönüştürücü içinde string.Format() fonksiyonu ile çözülebilen bir şablon dizesi döndürmelidir. Bu durumda beklenen dönüş dizesi örnekleri şunlardır: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}')

```csharp
public CssUrlMakingStrategy CustomStrategyOfCssUrlCreation;
```

### Ayrıca Bakınız

* delegate [CssUrlMakingStrategy](../../htmlsaveoptions.cssurlmakingstrategy/)
* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)