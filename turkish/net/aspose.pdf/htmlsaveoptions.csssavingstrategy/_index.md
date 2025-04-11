---
title: Delegate HtmlSaveOptions.CssSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Bu özelliğe, PDF'den HTML'ye dönüştürme sırasında oluşturulan bir CSS parçasının işlenmesini ve/veya kaydedilmesini uygulayan özel bir strateji atayabilirsiniz. Bu durumda, akışa veya diske kaydetme gibi işlemler bu özel kodda yapılmalıdır.
type: docs
weight: 5590
url: /tr/net/aspose.pdf/htmlsaveoptions.csssavingstrategy/
---
## HtmlSaveOptions.CssSavingStrategy delegesi

Bu özelliğe, PDF'den HTML'ye dönüştürme sırasında oluşturulan bir CSS parçasının işlenmesini ve/veya kaydedilmesini uygulayan özel bir strateji atayabilirsiniz. Bu durumda, işleme (örneğin akışa veya diske kaydetme) bu özel kodda yapılmalıdır.

```csharp
public delegate void CssSavingStrategy(CssSavingInfo partSavingInfo);
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| partSavingInfo | CssSavingInfo | sağlanan CSS parçasının kaydedilmesi için kullanılabilecek veri kümesini temsil eder |

### Ayrıca Bakınız

* sınıf [CssSavingInfo](../htmlsaveoptions.csssavinginfo/)
* sınıf [HtmlSaveOptions](../htmlsaveoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)