---
title: OperatorCollection.Item
second_title: Aspose.PDF for .NET API Reference
description: Proprietà OperatorCollection. Ottiene l'operatore per il suo indice
type: docs
weight: 40
url: /it/net/aspose.pdf/operatorcollection/item/
---
## Indicizzatore OperatorCollection

Ottiene l'operatore per il suo indice.

```csharp
public override Operator this[int index] { get; set; }
```

| Parametro | Descrizione |
| --- | --- |
| index | Indice dell'operatore. La numerazione inizia da 1. |

### Valore di ritorno

Operatore dall'indice richiesto

## Esempi

L'esempio dimostra come ottenere l'operatore dei contenuti della pagina per indice.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
Operator first = oc[1];
```

### Vedi Anche

* classe [Operator](../../operator/)
* classe [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)