---
title: OutputIntents.Item
second_title: Aspose.PDF for .NET API Reference
description: Proprietà OutputIntents. Ottiene l'intento di output all'indice specificato
type: docs
weight: 30
url: /it/net/aspose.pdf/outputintents/item/
---
## Indicizzatore OutputIntents

Ottiene l'intento di output all'*indice* specificato.

```csharp
public OutputIntent this[int index] { get; }
```

| Parametro | Descrizione |
| --- | --- |
| index | L'indice basato su zero dell'intento di output da ottenere. |

### Valore di Ritorno

L'intento di output all'*indice* specificato.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | *index* è minore di 0 o *index* è uguale o maggiore di [`Count`](../count/). |
| InvalidOperationException | Il documento che contiene la collezione non ha un catalogo per accedere agli OutputIntents. |

### Vedi Anche

* classe [OutputIntent](../../outputintent/)
* classe [OutputIntents](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)