---
title: Contents
second_title: Aspose.PDF for .NET API Referansı
description: Sayfanın içerik akışındaki operatörlerin koleksiyonunu alır. OperatorCollectionaspose.pdf/operatorcollection
type: docs
weight: 90
url: /tr/net/aspose.pdf/page/contents/
---
## Page.Contents property

Sayfanın içerik akışındaki operatörlerin koleksiyonunu alır. [`OperatorCollection`](../../operatorcollection)

```csharp
public OperatorCollection Contents { get; }
```

### Örnekler

Örnek, sayfanın operatör akışının nasıl taranacağını gösterir.

```csharp
Document document = new Document("sample.pdf");
Operators contents = document.Pages[1].Contents;
foreach(Operator op in contents)
{
    Console.WriteLine(op);
}
```

### Ayrıca bakınız

* class [OperatorCollection](../../operatorcollection)
* class [Page](../../page)
* ad alanı [Aspose.Pdf](../../page)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
