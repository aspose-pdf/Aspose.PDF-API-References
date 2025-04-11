---
title: Page.ArtBox
second_title: Aspose.PDF for .NET API Reference
description: Sayfa özelliği. Sayfanın sanat kutusunu alır veya ayarlar
type: docs
weight: 30
url: /tr/net/aspose.pdf/page/artbox/
---
## Page.ArtBox özelliği

Sayfanın sanat kutusunu alır veya ayarlar.

```csharp
public Rectangle ArtBox { get; set; }
```

## Örnekler

Örnek, sayfanın sanat kutusunu almanın nasıl yapılacağını gösterir:

```csharp
Document document = new Document("sample.pdf");
Rectangle artBox = document.Pages[1].ArtBox;
```

### Ayrıca Bakınız

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)