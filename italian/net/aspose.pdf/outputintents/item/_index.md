---
title: "OutputIntents.Item"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà OutputIntents. Ottiene l'output intent all'indice specificato."
type: docs
weight: 30
url: /it/net/aspose.pdf/outputintents/item/
---
## OutputIntents indexer

Ottiene l'output intent all'*index* specificato.

```csharp
public OutputIntent this[int index] { get; }
```

| Parametro | Descrizione |
| --- | --- |
| index | L'indice a base zero dell'output intent da ottenere. |

### Valore di ritorno

L'output intent all'*index* specificato.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | *index* è minore di 0 o *index* è uguale a o maggiore di [`Count`](../count/). |
| InvalidOperationException | Il documento che contiene la collezione non ha un catalogo per accedere a OutputIntents. |

### Vedi anche

* class [OutputIntent](../../outputintent/)
* class [OutputIntents](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


