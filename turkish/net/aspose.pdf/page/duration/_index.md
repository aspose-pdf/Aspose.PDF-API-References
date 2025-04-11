---
title: Page.Duration
second_title: Aspose.PDF for .NET API Reference
description: Sayfa özelliği. Sayfa görüntüleme süresini alır veya ayarlar. Bu, sayfanın sunum sırasında görüntüleneceği süredir. Süre tanımlı değilse 1 döner.
type: docs
weight: 110
url: /tr/net/aspose.pdf/page/duration/
---
## Sayfa.Süre özelliği

Sayfa görüntüleme süresini alır veya ayarlar. Bu, sayfanın sunum sırasında görüntüleneceği süredir. Süre tanımlı değilse -1 döner.

```csharp
public double Duration { get; set; }
```

## Örnekler

Örnek, sayfa süresinin nasıl alınacağını gösterir.

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
int pageRect = page.Duration;
```

### Ayrıca Bakınız

* sınıf [Sayfa](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)