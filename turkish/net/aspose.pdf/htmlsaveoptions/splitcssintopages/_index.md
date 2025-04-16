---
title: HtmlSaveOptions.SplitCssIntoPages
second_title: Aspose.PDF for .NET API Reference
description: HtmlSaveOptions özelliği. multipage-mode seçildiğinde bu öznitelik, her sonuç HTML sayfası için ayrı bir CSS dosyası oluşturulup oluşturulmayacağını belirler. Varsayılan olarak, bu öznitelik false'tur; bu nedenle oluşturulan tüm sayfalar için tek büyük ortak bir CSS oluşturulacaktır. Bu modda oluşturulan tüm CSS'lerin toplam boyutu, genellikle tek büyük bir CSS dosyasının boyutundan çok daha fazladır; çünkü bu durumda CSS sınıfları her sayfa için birden fazla CSS dosyasında yinelenmektedir. Dolayısıyla, bu ayar ancak her HTML sayfasının gelecekte bağımsız olarak işlenmesiyle ilgileniyorsanız ve bu nedenle her bir sayfanın CSS boyutu en kritik konu ise kullanılmalıdır.
type: docs
weight: 190
url: /tr/net/aspose.pdf/htmlsaveoptions/splitcssintopages/
---
## HtmlSaveOptions.SplitCssIntoPages özelliği

multipage-mode seçildiğinde (yani 'SplitIntoPages' true iken), bu öznitelik her bir sonuç HTML sayfası için ayrı bir CSS dosyası oluşturulup oluşturulmayacağını belirler. Varsayılan olarak, bu öznitelik false'tur; bu nedenle tüm oluşturulan sayfalar için tek büyük ortak bir CSS oluşturulacaktır. Bu modda (sayfa başına bir CSS) oluşturulan tüm CSS'lerin toplam boyutu, genellikle tek büyük bir CSS dosyasının boyutundan çok daha fazladır, çünkü bu durumda CSS sınıfları yinelenmekte ve her sayfa için birden fazla CSS dosyasında aynı sınıflar yer almaktadır. Dolayısıyla, bu ayar ancak her HTML sayfasının gelecekte bağımsız olarak işlenmesiyle ilgileniyorsanız kullanılması uygundur ve bu durumda her bir sayfanın CSS boyutu en kritik konudur.

```csharp
public bool SplitCssIntoPages { get; set; }
```

### Ayrıca Bakınız

* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)