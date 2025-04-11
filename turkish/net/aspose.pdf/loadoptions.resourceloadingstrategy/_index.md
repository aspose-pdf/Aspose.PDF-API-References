---
title: Delegate LoadOptions.ResourceLoadingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Bazen, dış kaynakların (görüntüler veya CSS gibi) dahili yükleyicisinin kullanımını önlemek ve istenen kaynakları bir yerden alacak özel bir yöntem sağlamak gerekir. Örneğin, Aspose.Pdf'in bulutta kullanımı sırasında, referans verilen dosyalara doğrudan erişim imkansızdır ve özel bir yönteme yerleştirilen bazı özel kod kullanılmalıdır. Bu delege, böyle bir özel yönteminin imzasını tanımlar.
type: docs
weight: 6160
url: /tr/net/aspose.pdf/loadoptions.resourceloadingstrategy/
---
## LoadOptions.ResourceLoadingStrategy delegesi

Bazen, dış kaynakların (görüntüler veya CSS gibi) dahili yükleyicisinin kullanımını önlemek ve istenen kaynakları bir yerden alacak özel bir yöntem sağlamak gerekir. Örneğin, Aspose.Pdf'in bulutta kullanımı sırasında, referans verilen dosyalara doğrudan erişim imkansızdır ve özel bir yönteme yerleştirilen bazı özel kod kullanılmalıdır. Bu delege, böyle bir özel yönteminin imzasını tanımlar.

```csharp
public delegate ResourceLoadingResult ResourceLoadingStrategy(string resourceURI);
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| resourceURI | String | Kaynak URI'si. |

### Dönüş Değeri

ResourceLoadingResult nesnesi.

### Ayrıca Bakınız

* sınıf [ResourceLoadingResult](../loadoptions.resourceloadingresult/)
* sınıf [LoadOptions](../loadoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)