---
title: Page.TrimBox
second_title: Aspose.PDF for .NET API Reference
description: Sayfa özelliği. Sayfanın trim kutusunu alır veya ayarlar
type: docs
weight: 290
url: /tr/net/aspose.pdf/page/trimbox/
---
## Page.TrimBox özelliği

Sayfanın trim kutusunu alır veya ayarlar.

```csharp
public Rectangle TrimBox { get; set; }
```

## Örnekler

Örnek, sayfanın trim kutusunu almanın nasıl yapılacağını gösterir:

```csharp
Document document = new Document("sample.pdf");
Rectangle trimBox = document.Pages[1].TrimBox;
```

### Ayrıca Bakınız

* sınıf [Rectangle](../../rectangle/)
* sınıf [Page](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)