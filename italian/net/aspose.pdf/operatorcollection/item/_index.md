---
title: Item
second_title: Aspose.PDF per .NET API Reference
description: Ottiene loperatore in base al suo indice.
type: docs
weight: 40
url: /it/net/aspose.pdf/operatorcollection/item/
---
## OperatorCollection indexer

Ottiene l'operatore in base al suo indice.

```csharp
public override Operator this[int index] { get; set; }
```

| Parametro | Descrizione |
| --- | --- |
| index | Indice dell'operatore. La numerazione inizia da 1. |

### Valore di ritorno

Operatore dall'indice richiesto

### Esempi

L'esempio mostra come ottenere l'operatore del contenuto della pagina per indice.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
Operator first = oc[1];
```

### Guarda anche

* class [Operator](../../operator)
* class [OperatorCollection](../../operatorcollection)
* spazio dei nomi [Aspose.Pdf](../../operatorcollection)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
