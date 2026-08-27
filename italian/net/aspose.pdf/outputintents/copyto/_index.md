---
title: "OutputIntents.CopyTo"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo OutputIntents. Copia gli elementi della raccolta nell'array a partire dal particolare arrayIndex nell'array"
type: docs
weight: 70
url: /it/net/aspose.pdf/outputintents/copyto/
---
## OutputIntents.CopyTo method

Copia gli elementi della raccolta nell'*array*, a partire dal particolare *arrayIndex* nell'array.

```csharp
public void CopyTo(OutputIntent[] array, int arrayIndex)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | OutputIntent[] | L'array monodimensionale che è la destinazione degli output intent copiati dalla raccolta. L'array deve avere un indicizzamento a base zero. |
| arrayIndex | Int32 | L'indice a base zero in *array* al quale inizia la copia. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *array* è nullo. |
| ArgumentOutOfRangeException | *arrayIndex* è minore di 0. |
| ArgumentException | Il numero di elementi nella sorgente [`OutputIntents`](../) è maggiore dello spazio disponibile da *arrayIndex* fino alla fine dell'*array* di destinazione. |

### Vedi anche

* class [OutputIntent](../../outputintent/)
* class [OutputIntents](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


