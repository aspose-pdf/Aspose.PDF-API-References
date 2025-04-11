---
title: Page.BleedBox
second_title: Aspose.PDF for .NET API Reference
description: Sayfa özelliği. Sayfanın bleed kutusunu alır veya ayarlar
type: docs
weight: 70
url: /tr/net/aspose.pdf/page/bleedbox/
---
## Sayfa.BleedBox özelliği

Sayfanın bleed kutusunu alır veya ayarlar.

```csharp
public Rectangle BleedBox { get; set; }
```

## Örnekler

Örnek, sayfanın bleed kutusunu almanın nasıl yapılacağını gösterir:

```csharp
Document document = new Document("sample.pdf");
Rectangle bleedBox = document.Pages[1].BleedBox;
```

### Ayrıca Bakınız

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)