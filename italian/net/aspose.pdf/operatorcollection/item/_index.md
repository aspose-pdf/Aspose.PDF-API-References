---
title: "OperatorCollection.Item"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà OperatorCollection. Ottiene l'operatore per il suo indice"
type: docs
weight: 40
url: /it/net/aspose.pdf/operatorcollection/item/
---
## OperatorCollection indexer

Restituisce l'operatore in base al suo indice.

```csharp
public override Operator this[int index] { get; set; }
```

| Parametro | Descrizione |
| --- | --- |
| index | Indice dell'operatore. La numerazione inizia da 1. |

### Valore di ritorno

Operatore dall'indice richiesto

## Esempi

L'esempio dimostra come ottenere l'operatore del contenuto della pagina per indice.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
Operator first = oc[1];
```

### Vedi anche

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


