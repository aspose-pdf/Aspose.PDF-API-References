---
title: Delegate HtmlSaveOptions.CssUrlMakingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Bu özelliğe, oluşturulan HTML belgesinde referans verilen CSS'nin URL'sinin oluşturulmasını uygulayan özel bir yöntemden oluşturulan bir delege atayabilirsiniz. Örneğin, HTML'de "otherPage.ASPXCssIDzjjkklj" olarak referans verilen CSS'yi oluşturmak istiyorsanız, bu özel stratejinin "otherPage.ASPXCssIDzjjkklj" döndürmesi gerekir.
type: docs
weight: 5600
url: /tr/net/aspose.pdf/htmlsaveoptions.cssurlmakingstrategy/
---
## HtmlSaveOptions.CssUrlMakingStrategy delegesi

Bu özelliğe, oluşturulan HTML belgesinde referans verilen CSS'nin URL'sinin oluşturulmasını uygulayan özel bir yöntemden oluşturulan bir delege atayabilirsiniz. Örneğin, HTML'de "otherPage.ASPX?CssID=zjjkklj" olarak referans verilen CSS'yi oluşturmak istiyorsanız, bu özel stratejinin "otherPage.ASPX?CssID=zjjkklj" döndürmesi gerekir.

```csharp
public delegate string CssUrlMakingStrategy(CssUrlRequestInfo cssUrlRequestInfo);
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cssUrlRequestInfo | CssUrlRequestInfo | CSS'nin URL'sinin oluşturulmasında kullanılabilecek veri kümesini temsil eder |

### Dönüş Değeri

CSS'nin URL'sini veya URL'nin şablonunu temsil eden bir dize döndürmelidir.

### Ayrıca Bakınız

* sınıf [CssUrlRequestInfo](../htmlsaveoptions.cssurlrequestinfo/)
* sınıf [HtmlSaveOptions](../htmlsaveoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)