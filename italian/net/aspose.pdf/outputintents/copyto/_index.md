---
title: OutputIntents.CopyTo
second_title: Aspose.PDF for .NET API Reference
description: Metodo OutputIntents. Copia gli elementi della collezione nell'array a partire dal particolare arrayIndex nell'array
type: docs
weight: 70
url: /it/net/aspose.pdf/outputintents/copyto/
---
## Metodo OutputIntents.CopyTo

Copia gli elementi della collezione nell'*array*, a partire dal particolare *arrayIndex* nell'array.

```csharp
public void CopyTo(OutputIntent[] array, int arrayIndex)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | OutputIntent[] | L'array monodimensionale che è la destinazione degli output intents copiati dalla collezione. L'array deve avere indicizzazione basata su zero. |
| arrayIndex | Int32 | L'indice basato su zero in *array* da cui inizia la copia. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *array* è nullo. |
| ArgumentOutOfRangeException | *arrayIndex* è minore di 0. |
| ArgumentException | Il numero di elementi nella sorgente [`OutputIntents`](../) è maggiore dello spazio disponibile da *arrayIndex* alla fine dell'*array* di destinazione. |

### Vedi Anche

* classe [OutputIntent](../../outputintent/)
* classe [OutputIntents](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)