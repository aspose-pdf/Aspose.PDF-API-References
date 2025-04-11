---
title: Page.Contents
second_title: Aspose.PDF for .NET API Reference
description: Sayfa özelliği. Sayfanın içerik akışındaki operatörlerin koleksiyonunu alır. OperatorCollection
type: docs
weight: 90
url: /tr/net/aspose.pdf/page/contents/
---
## Sayfa.Içerikleri özelliği

Sayfanın içerik akışındaki operatörlerin koleksiyonunu alır. [`OperatorCollection`](../../operatorcollection/)

```csharp
public OperatorCollection Contents { get; }
```

## Örnekler

Örnek, sayfanın operatör akışını taramanın nasıl yapılacağını gösterir.

```csharp
Document document = new Document("sample.pdf");
Operators contents = document.Pages[1].Contents;
foreach(Operator op in contents)
{
    Console.WriteLine(op);
}
```

### Ayrıca Bakınız

* sınıf [OperatorCollection](../../operatorcollection/)
* sınıf [Sayfa](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)