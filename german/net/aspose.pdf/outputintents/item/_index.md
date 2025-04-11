---
title: OutputIntents.Item
second_title: Aspose.PDF for .NET API Reference
description: OutputIntents-Eigenschaft. Holt die Ausgabeabsicht am angegebenen Index
type: docs
weight: 30
url: /de/net/aspose.pdf/outputintents/item/
---
## OutputIntents-Indexer

Holt die Ausgabeabsicht am angegebenen *Index*.

```csharp
public OutputIntent this[int index] { get; }
```

| Parameter | Beschreibung |
| --- | --- |
| index | Der nullbasierte Index der zu holenden Ausgabeabsicht. |

### Rückgabewert

Die Ausgabeabsicht am angegebenen *Index*.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | *index* ist kleiner als 0 oder *index* ist gleich oder größer als [`Count`](../count/). |
| InvalidOperationException | Das Dokument, das die Sammlung enthält, hat kein Katalog, um auf die OutputIntents zuzugreifen. |

### Siehe Auch

* Klasse [OutputIntent](../../outputintent/)
* Klasse [OutputIntents](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)