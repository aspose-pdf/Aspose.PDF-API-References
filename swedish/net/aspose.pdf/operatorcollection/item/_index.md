---
title: OperatorCollection.Item
second_title: Aspose.PDF for .NET API Reference
description: OperatorCollection-egenskap. Hämtar operatorn efter dess index
type: docs
weight: 40
url: /sv/net/aspose.pdf/operatorcollection/item/
---
## OperatorCollection indexer

Hämtar operatorn efter dess index.

```csharp
public override Operator this[int index] { get; set; }
```

| Parameter | Beskrivning |
| --- | --- |
| index | Index för operatorn. Numreringen börjar från 1. |

### Returvärde

Operator från begärt index

## Exempel

Exemplet visar hur man hämtar operatorn för sidinnehåll efter index.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
Operator first = oc[1];
```

### Se Även

* klass [Operator](../../operator/)
* klass [OperatorCollection](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* samling [Aspose.PDF](../../../)