---
title: Table.ImportDataTable
second_title: Aspose.PDF for .NET API Reference
description: Tabellenmethode. Importiert Daten aus System.Data.DataTable in Aspose.Pdf.Table
type: docs
weight: 260
url: /de/net/aspose.pdf/table/importdatatable/
---
## ImportDataTable(DataTable, bool, int, int) {#importdatatable_1}

Importiert Daten aus System.Data.DataTable in Aspose.Pdf.Table

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesImported, 
    int firstFilledRow, int firstFilledColumn)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| importedDataTable | DataTable | Quellinstanz von System.Data.DataTable |
| isColumnNamesImported | Boolean | Gibt an, ob die Spaltennamen als erste Zeile importiert werden |
| firstFilledRow | Int32 | Gibt die nullbasierte Nummer der ersten Zeile in der Zieltabelle an, von der der Import beginnen soll. Wenn eine Zeile mit dieser Nummer (und einige vorherige Zeilen) in der Zieltabelle fehlen, werden sie zuerst erstellt |
| firstFilledColumn | Int32 | Gibt die Nummer der ersten Zielspalte in der Zieltabelle an, die Spalte muss vor Beginn des Imports in der Zieltabelle vorhanden sein |

### Siehe auch

* Klasse [Table](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, bool, int, byte, int, int, bool) {#importdatatable}

Importiert ein DataTable-Objekt in die Tabelle.

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesShown, 
    int firstFilledRow, byte firstFilledColumn, int maxRows, int maxColumns, 
    bool isHtmlSupported = false)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| importedDataTable | DataTable | Das zu importierende DataTable-Objekt. |
| isColumnNamesShown | Boolean | Gibt an, ob die Spaltennamen der Quell-Datentabelle als erste Zeile importiert werden. |
| firstFilledRow | Int32 | Gibt die nullbasierte Nummer der ersten Zeile in der Zieltabelle an, von der der Import beginnen soll. Wenn eine Zeile mit dieser Nummer (und einige vorherige Zeilen) in der Zieltabelle fehlen, werden sie zuerst erstellt |
| firstFilledColumn | Byte | Gibt die Nummer der ersten Zielspalte in der Zieltabelle an, die Spalte muss vor Beginn des Imports in der Zieltabelle vorhanden sein |
| maxRows | Int32 | Maximale Anzahl von Zeilen, die aus der Quelltabelle importiert werden sollen. |
| maxColumns | Int32 | Maximale Anzahl von Spalten, die aus der Quelltabelle importiert werden sollen. |
| isHtmlSupported | Boolean | Gibt an, ob der Text ein HTML-String ist. |

### Siehe auch

* Klasse [Table](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, int[], int[], int, int, bool, bool) {#importdatatable_2}

Importiert ein DataTable-Objekt, jedoch nicht als ganze Einheit. Nur bestimmte Zeilen und Spalten werden importiert.

```csharp
public void ImportDataTable(DataTable importedDataTable, int[] sourceRowList, 
    int[] sourceColumnList, int firstFilledRow, int firstFilledColumn, 
    bool showColumnNamesAsFirstRow, bool isHtmlSupported = false)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| importedDataTable | DataTable | Das zu importierende DataTable-Objekt. |
| sourceRowList | Int32[] | Das Array von Nummern der Zeilen im Quell-DataTable-Objekt, die importiert werden müssen. Die Liste darf nicht null sein und muss nur Nummern vorhandener Zeilen enthalten, andernfalls wird eine Ausnahme ausgelöst. |
| sourceColumnList | Int32[] | Das Array von Nummern der Spalten im Quell-DataTable-Objekt, die importiert werden müssen. Die Liste darf nicht null sein und muss nur Nummern vorhandener Spalten enthalten, andernfalls wird eine Ausnahme ausgelöst. |
| firstFilledRow | Int32 | Die nullbasierte Zeilennummer der ersten Zelle in der Zieltabelle, von der der Import beginnen soll. Wenn die Zieltabelle diese Zeile nicht enthält, wird sie (und alle vorherigen, falls erforderlich) erstellt |
| firstFilledColumn | Int32 | Die nullbasierte Spaltennummer der ersten Zelle in der Zieltabelle, von der der Import beginnen soll. Die Zieltabelle muss diese Spalte vor Beginn des Imports enthalten, andernfalls wird eine Ausnahme ausgelöst. |
| showColumnNamesAsFirstRow | Boolean | Gibt an, ob die Spaltennamen der Quell-Datentabelle als erste Zeile importiert werden. |
| isHtmlSupported | Boolean | Gibt an, ob der Text ein HTML-String ist. |

### Siehe auch

* Klasse [Table](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)