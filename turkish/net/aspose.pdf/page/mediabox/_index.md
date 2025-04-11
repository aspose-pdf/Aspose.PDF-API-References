---
title: Page.MediaBox
second_title: Aspose.PDF for .NET API Reference
description: Sayfa özelliği. Sayfanın medya kutusunu alır veya ayarlar
type: docs
weight: 180
url: /tr/net/aspose.pdf/page/mediabox/
---
## Sayfa.MediaBox özelliği

Sayfanın medya kutusunu alır veya ayarlar.

```csharp
public Rectangle MediaBox { get; set; }
```

## Örnekler

Örnek, sayfanın medya kutusunu almanın nasıl yapılacağını gösterir:

```csharp
Document document = new Document("sample.pdf");
Rectangle mediaBox = document.Pages[1].MediaBox;
```

### Ayrıca Bakınız

* sınıf [Rectangle](../../rectangle/)
* sınıf [Page](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)