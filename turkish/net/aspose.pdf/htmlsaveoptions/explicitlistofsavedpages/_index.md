---
title: HtmlSaveOptions.ExplicitListOfSavedPages
second_title: Aspose.PDF for .NET API Reference
description: HtmlSaveOptions özelliği. Bu özellik ile belgenin hangi sayfalarının dönüştürüleceğini açıkça tanımlayabilirsiniz. Bu listedeki sayfalar 1 tabanlı numaralara sahip olmalıdır. Yani, geçerli sayfa numaraları 1...NumberOfPagesInConvertedDocument aralığından alınmalıdır. Bu listedeki sayfaların görünme sırası, sonuç HTML sayfalarındaki sıralarını etkilemez; sonuç sayfaları her zaman kaynak PDF'de mevcut oldukları sırayla gidecektir. Bu liste null ise - varsayılan olarak olduğu gibi, tüm sayfalar dönüştürülecektir. Bu listedeki herhangi bir sayfa numarası mevcut sayfaların aralığının dışına çıkarsa bir istisna fırlatılacaktır.
type: docs
weight: 70
url: /tr/net/aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/
---
## HtmlSaveOptions.ExplicitListOfSavedPages özelliği

Bu özellik ile belgenin hangi sayfalarının dönüştürüleceğini açıkça tanımlayabilirsiniz. Bu listedeki sayfalar 1 tabanlı numaralara sahip olmalıdır. Yani, geçerli sayfa numaraları (1...[NumberOfPagesInConvertedDocument]) aralığından alınmalıdır. Bu listedeki sayfaların görünme sırası, sonuç HTML sayfa(ları) üzerindeki sıralarını etkilemez; sonuç sayfaları her zaman kaynak PDF'de mevcut oldukları sırayla gidecektir. Bu liste null ise (varsayılan olarak olduğu gibi), tüm sayfalar dönüştürülecektir. Bu listedeki herhangi bir sayfa numarası mevcut sayfaların aralığının dışına çıkarsa (1-[amountOfPagesInDocument]) bir istisna fırlatılacaktır.

```csharp
public int[] ExplicitListOfSavedPages { get; set; }
```

### Ayrıca Bakınız

* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)