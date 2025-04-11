---
title: Page.Resources
second_title: Aspose.PDF for .NET API Reference
description: Sayfa özelliği. Sayfa kaynaklarını alır. Kaynaklar nesnesi, resim, form ve yazı tipleri koleksiyonlarını içerir. Kaynaklar
type: docs
weight: 240
url: /tr/net/aspose.pdf/page/resources/
---
## Sayfa.Kaynakları özelliği

Sayfa kaynaklarını alır. Kaynaklar nesnesi, resim, form ve yazı tipleri koleksiyonlarını içerir. `Kaynaklar`

```csharp
public Resources Resources { get; }
```

## Örnekler

Örnek, sayfa resimleri arasında tarama yapmayı gösterir:

```csharp
Document document = new Document("sample.pdf");
DocumentActions actions = document.Actions;
Resources resources = document.Pages[1].Resources;
foreach(XImage image in resources.Images)
{
  Console.WriteLine(image.Width + ":" + image.Height);
}
```

### Ayrıca Bakınız

* sınıf [Kaynaklar](../../resources/)
* sınıf [Sayfa](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)