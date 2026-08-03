---
title: "Table.ImportDataView"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Table‑metod. Importerar data från ett DataView‑objekt till tabellen."
type: docs
weight: 270
url: /sv/net/aspose.pdf/table/importdataview/
---
## Table.ImportDataView method

Importerar data från ett DataView‑objekt till tabellen.

```csharp
public void ImportDataView(DataView sourceDataView, bool isColumnNamesImported, int firstFilledRow, 
    int firstFilledColumn, int maxRows, int maxColumns)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceDataView | DataView | DataView-objektet som ska importeras. |
| isColumnNamesImported | Boolean | Anger om kolumnnamnen ska importeras som den första raden. |
| firstFilledRow | Int32 | Det nollbaserade radnumret för den första cellen i mål‑tabellen där importen ska börja. Om mål‑tabellen inte innehåller den raden skapas den (och alla föregående vid behov). |
| firstFilledColumn | Int32 | Det nollbaserade kolumnnumret för den första cellen i måltabellen från vilken importen ska börja. Måltabellen måste innehålla den kolumnen innan importen startar, annars kastas ett undantag. |
| maxRows | Int32 | Maximalt antal rader som ska importeras från käll‑datavy. |
| maxColumns | Int32 | Maximalt antal kolumner som ska importeras från käll‑datavy. |

### Se även

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


