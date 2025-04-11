---
title: Table.ImportDataView
second_title: Aspose.PDF for .NET API Reference
description: Tabellenmethode. Importiert die Daten eines DataView-Objekts in die Tabelle
type: docs
weight: 270
url: /de/net/aspose.pdf/table/importdataview/
---
## Table.ImportDataView-Methode

Importiert die Daten eines DataView-Objekts in die Tabelle.

```csharp
public void ImportDataView(DataView sourceDataView, bool isColumnNamesImported, int firstFilledRow, 
    int firstFilledColumn, int maxRows, int maxColumns)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceDataView | DataView | Das zu importierende DataView-Objekt. |
| isColumnNamesImported | Boolean | Gibt an, ob die Spaltennamen als erste Zeile importiert werden. |
| firstFilledRow | Int32 | Die nullbasierte Zeilennummer der ersten Zelle in der Zieltabelle, von der der Import beginnen wird. Wenn die Zieltabelle diese Zeile nicht enthält, wird sie (und alle vorherigen, falls erforderlich) erstellt. |
| firstFilledColumn | Int32 | Die nullbasierte Spaltennummer der ersten Zelle in der Zieltabelle, von der der Import beginnen wird. Die Zieltabelle muss diese Spalte enthalten, bevor der Import beginnt, andernfalls wird eine Ausnahme ausgelöst. |
| maxRows | Int32 | Maximale Anzahl von Zeilen, die aus dem Quell-DataView importiert werden sollen. |
| maxColumns | Int32 | Maximale Spalten, die aus dem Quell-DataView importiert werden sollen. |

### Siehe auch

* Klasse [Table](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)