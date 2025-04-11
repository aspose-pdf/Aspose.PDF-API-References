---
title: OperatorCollection.Item
second_title: Aspose.PDF for .NET API Reference
description: OperatorCollection özelliği. Operatörü indeksine göre alır
type: docs
weight: 40
url: /tr/net/aspose.pdf/operatorcollection/item/
---
## OperatorCollection indeksleyici

Operatörü indeksine göre alır.

```csharp
public override Operator this[int index] { get; set; }
```

| Parametre | Açıklama |
| --- | --- |
| index | Operatörün indeksi. Numara 1'den başlar. |

### Dönüş Değeri

İstenen indeksten operatör

## Örnekler

Örnek, sayfa içeriklerinin operatörünü indeksine göre almayı gösterir.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
Operator first = oc[1];
```

### Ayrıca Bakınız

* sınıf [Operator](../../operator/)
* sınıf [OperatorCollection](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)