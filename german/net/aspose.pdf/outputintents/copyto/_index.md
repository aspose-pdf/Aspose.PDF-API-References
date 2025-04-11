---
title: OutputIntents.CopyTo
second_title: Aspose.PDF for .NET API Reference
description: OutputIntents-Methode. Kopiert die Elemente der Sammlung in das *array*, beginnend bei dem bestimmten *arrayIndex* in das Array.
type: docs
weight: 70
url: /de/net/aspose.pdf/outputintents/copyto/
---
## OutputIntents.CopyTo-Methode

Kopiert die Elemente der Sammlung in das *array*, beginnend bei dem bestimmten *arrayIndex* in das Array.

```csharp
public void CopyTo(OutputIntent[] array, int arrayIndex)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | OutputIntent[] | Das eindimensionale Array, das das Ziel der aus der Sammlung kopierten Ausgabebestimmungen ist. Das Array muss nullbasiertes Indexing haben. |
| arrayIndex | Int32 | Der nullbasierte Index im *array*, an dem das Kopieren beginnt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *array* ist null. |
| ArgumentOutOfRangeException | *arrayIndex* ist kleiner als 0. |
| ArgumentException | Die Anzahl der Elemente in der Quelle [`OutputIntents`](../) ist größer als der verfügbare Platz von *arrayIndex* bis zum Ende des Ziel-*array*. |

### Siehe auch

* Klasse [OutputIntent](../../outputintent/)
* Klasse [OutputIntents](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)