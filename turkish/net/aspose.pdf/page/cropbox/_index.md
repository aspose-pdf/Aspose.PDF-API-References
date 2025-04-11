---
title: Page.CropBox
second_title: Aspose.PDF for .NET API Reference
description: Sayfa özelliği. Sayfanın kesim kutusunu alır veya ayarlar
type: docs
weight: 100
url: /tr/net/aspose.pdf/page/cropbox/
---
## Sayfa.CropBox özelliği

Sayfanın kesim kutusunu alır veya ayarlar.

```csharp
public Rectangle CropBox { get; set; }
```

## Örnekler

Örnek, sayfanın kesim kutusunu almanın nasıl yapılacağını gösterir:

```csharp
Document document = new Document("sample.pdf");
Rectangle cropBox = document.Pages[1].CropBox;
```

### Ayrıca Bakınız

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)