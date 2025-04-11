---
title: Table.ImportDataView
second_title: Aspose.PDF for .NET API Reference
description: Tabellmetod. Importerar data från ett DataView-objekt till tabellen
type: docs
weight: 270
url: /sv/net/aspose.pdf/table/importdataview/
---
## Table.ImportDataView metod

Importerar data från ett DataView-objekt till tabellen.

```csharp
public void ImportDataView(DataView sourceDataView, bool isColumnNamesImported, int firstFilledRow, 
    int firstFilledColumn, int maxRows, int maxColumns)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceDataView | DataView | DataView-objektet som ska importeras. |
| isColumnNamesImported | Boolean | Indikerar om kolumnnamnen kommer att importeras som första rad. |
| firstFilledRow | Int32 | Det nollbaserade radnumret för den första cellen i måltabellen från vilken importen kommer att börja. Om måltabellen inte innehåller den raden, kommer den (och alla föregående om nödvändigt) att skapas |
| firstFilledColumn | Int32 | Det nollbaserade kolumnnumret för den första cellen i måltabellen från vilken importen kommer att börja. Måltabellen måste innehålla den kolumnen innan importen börjar, annars kommer ett undantag att kastas. |
| maxRows | Int32 | Maximalt antal rader som ska importeras från källdataview. |
| maxColumns | Int32 | Maximala kolumner som ska importeras från källdataview. |

### Se Även

* klass [Table](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* samling [Aspose.PDF](../../../)