---
title: Item
second_title: Aspose.PDF for .NET API Referansı
description: Operatörü indeksine göre alır.
type: docs
weight: 40
url: /tr/net/aspose.pdf/operatorcollection/item/
---
## OperatorCollection indexer

Operatörü indeksine göre alır.

```csharp
public override Operator this[int index] { get; set; }
```

| Parametre | Tanım |
| --- | --- |
| index | Operatör indeksi. Numaralandırma 1'den başlar. |

### Geri dönüş değeri

İstenen dizinden operatör

### Örnekler

Örnek, indekse göre sayfa içeriği operatörünün nasıl alınacağını gösterir.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
Operator first = oc[1];
```

### Ayrıca bakınız

* class [Operator](../../operator)
* class [OperatorCollection](../../operatorcollection)
* ad alanı [Aspose.Pdf](../../operatorcollection)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->