---
title: ImportDataView
second_title: Aspose.PDF für .NET-API-Referenz
description: Importiert aDataView Objektdaten in die Tabelle.
type: docs
weight: 270
url: /de/net/aspose.pdf/table/importdataview/
---
## Table.ImportDataView method

Importiert aDataView Objektdaten in die Tabelle.

```csharp
public void ImportDataView(DataView sourceDataView, bool isColumnNamesImported, int firstFilledRow, 
    int firstFilledColumn, int maxRows, int maxColumns)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceDataView | DataView | DasDataView zu importierendes Objekt. |
| isColumnNamesImported | Boolean | Gibt an, ob die Spaltennamen als erste Zeile importiert werden. |
| firstFilledRow | Int32 | Die nullbasierte Zeilennummer der ersten Zelle in der Zieltabelle, von der aus der Import beginnt. Wenn die Zieltabelle diese Zeile nicht enthält, wird sie (und alle vorherigen, falls erforderlich) erstellt |
| firstFilledColumn | Int32 | Die nullbasierte Spaltennummer der ersten Zelle in der Zieltabelle, ab der der Import beginnt. Die Zieltabelle muss diese Spalte enthalten, bevor der Import beginnt, andernfalls wird eine Ausnahme ausgelöst. |
| maxRows | Int32 | Maximale Anzahl von Zeilen, die aus der Quelldatenansicht importiert werden sollen. |
| maxColumns | Int32 | Maximale Spalten, die aus der Quelldatenansicht importiert werden sollen. |

### Siehe auch

* class [Table](../../table)
* namensraum [Aspose.Pdf](../../table)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
