---
title: "OperatorCollection.Item"
second_title: "Aspose.PDF för .NET API‑referens"
description: "OperatorCollection-egenskapen. Hämtar en operator efter dess index"
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

Exempel visar hur man hämtar en operator för sidinnehåll efter index.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
Operator first = oc[1];
```

### Se även

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


