---
title: OperatorCollection.Item
second_title: Aspose.PDF for .NET API Reference
description: OperatorCollection-Eigenschaft. Holt den Operator nach seinem Index
type: docs
weight: 40
url: /de/net/aspose.pdf/operatorcollection/item/
---
## OperatorCollection-Indexer

Holt den Operator nach seinem Index.

```csharp
public override Operator this[int index] { get; set; }
```

| Parameter | Beschreibung |
| --- | --- |
| index | Index des Operators. Die Nummerierung beginnt bei 1. |

### Rückgabewert

Operator vom angeforderten Index

## Beispiele

Das Beispiel zeigt, wie man den Operator des Seiteninhalts nach Index erhält.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
Operator first = oc[1];
```

### Siehe auch

* Klasse [Operator](../../operator/)
* Klasse [OperatorCollection](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)