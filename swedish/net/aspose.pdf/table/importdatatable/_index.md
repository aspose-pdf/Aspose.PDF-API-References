---
title: Table.ImportDataTable
second_title: Aspose.PDF for .NET API Reference
description: Table-metod. Importerar data från System.Data.DataTable till Aspose.Pdf.Table
type: docs
weight: 260
url: /sv/net/aspose.pdf/table/importdatatable/
---
## ImportDataTable(DataTable, bool, int, int) {#importdatatable_1}

Importerar data från System.Data.DataTable till Aspose.Pdf.Table

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesImported, 
    int firstFilledRow, int firstFilledColumn)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| importedDataTable | DataTable | källa instans av System.Data.DataTable |
| isColumnNamesImported | Boolean | specificerar om kolumnnamn kommer att importeras som första rad |
| firstFilledRow | Int32 | specificerar nollbaserat nummer på första rad i mål tabell från vilken importen kommer att börja, om rad med sådant nummer (och några föregående rader) saknas i mål tabell, kommer de att skapas först |
| firstFilledColumn | Int32 | specificerar nummer på första mål kolumn i mål tabell, kolumnen måste finnas i mål tabell innan importen börjar |

### Se Även

* klass [Table](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, bool, int, byte, int, int, bool) {#importdatatable}

Importerar ett DataTable-objekt till tabellen.

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesShown, 
    int firstFilledRow, byte firstFilledColumn, int maxRows, int maxColumns, 
    bool isHtmlSupported = false)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| importedDataTable | DataTable | DataTable-objektet som ska importeras. |
| isColumnNamesShown | Boolean | Specificerar om kolumnnamnen i källdatatabellen kommer att importeras som första rad. |
| firstFilledRow | Int32 | specificerar nollbaserat nummer på första rad i mål tabell från vilken importen kommer att börja, om rad med sådant nummer (och några föregående rader) saknas i mål tabell, kommer de att skapas först |
| firstFilledColumn | Byte | specificerar nummer på första mål kolumn i mål tabell, kolumnen måste finnas i mål tabell innan importen börjar |
| maxRows | Int32 | Maximalt antal rader som ska importeras från källtabellen. |
| maxColumns | Int32 | Maximalt antal kolumner som ska importeras från källtabellen. |
| isHtmlSupported | Boolean | Specificerar om texten är en html-sträng. |

### Se Även

* klass [Table](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, int[], int[], int, int, bool, bool) {#importdatatable_2}

Importerar ett DataTable-objekt, men inte som en hel enhet. Endast specificerade rader och kolumner importeras.

```csharp
public void ImportDataTable(DataTable importedDataTable, int[] sourceRowList, 
    int[] sourceColumnList, int firstFilledRow, int firstFilledColumn, 
    bool showColumnNamesAsFirstRow, bool isHtmlSupported = false)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| importedDataTable | DataTable | DataTable-objektet som ska importeras. |
| sourceRowList | Int32[] | Array av nummer på rader i käll DataTable-objektet som måste importeras. Listan får inte vara null och måste endast innehålla nummer på existerande rader, annars kommer ett undantag att kastas. |
| sourceColumnList | Int32[] | Array av nummer på kolumner i käll DataTable-objektet som måste importeras. Listan får inte vara null och måste endast innehålla nummer på existerande kolumner, annars kommer ett undantag att kastas. |
| firstFilledRow | Int32 | Det nollbaserade radnumret för den första cellen i mål tabell från vilken importen kommer att börja. Om mål tabell inte innehåller den raden, kommer den (och alla föregående om nödvändigt) att skapas |
| firstFilledColumn | Int32 | Det nollbaserade kolumnnumret för den första cellen i mål tabell från vilken importen kommer att börja. Mål tabell måste innehålla den kolumnen innan importen börjar, annars kommer ett undantag att kastas. |
| showColumnNamesAsFirstRow | Boolean | Specificerar om kolumnnamnen i källdatatabellen kommer att importeras som första rad. |
| isHtmlSupported | Boolean | Specificerar om texten är en html-sträng. |

### Se Även

* klass [Table](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)