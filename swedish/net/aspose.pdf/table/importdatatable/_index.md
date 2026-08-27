---
title: "Table.ImportDataTable"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Table-metod. Importerar data från System.Data.DataTable till Aspose.Pdf.Table"
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
| importedDataTable | DataTable | källinstans av System.Data.DataTable |
| isColumnNamesImported | Boolean | anger om kolumnnamn ska importeras som första rad |
| firstFilledRow | Int32 | anger nollbaserat nummer för den första raden i måltabellen från vilken importen ska starta; om raden med detta nummer (och några föregående rader) saknas i måltabellen, skapas de först |
| firstFilledColumn | Int32 | anger nummer för den första målkolumnen i måltabellen, kolumnen måste finnas i måltabellen innan importen startar |

### Se även

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, bool, int, byte, int, int, bool) {#importdatatable}

Importerar ett DataTable‑objekt till tabellen.

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesShown, 
    int firstFilledRow, byte firstFilledColumn, int maxRows, int maxColumns, 
    bool isHtmlSupported = false)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| importedDataTable | DataTable | DataTable-objektet som ska importeras. |
| isColumnNamesShown | Boolean | Anger om kolumnnamnen i källdatatabellen ska importeras som första rad. |
| firstFilledRow | Int32 | anger nollbaserat nummer för den första raden i måltabellen från vilken importen ska starta; om raden med detta nummer (och några föregående rader) saknas i måltabellen, skapas de först |
| firstFilledColumn | Byte | anger nummer för den första målkolumnen i måltabellen, kolumnen måste finnas i måltabellen innan importen startar |
| maxRows | Int32 | Maximalt antal rader som ska importeras från källtabellen. |
| maxColumns | Int32 | Maximalt antal kolumner som ska importeras från källtabellen. |
| isHtmlSupported | Boolean | Anger om texten är en HTML-sträng. |

### Se även

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, int[], int[], int, int, bool, bool) {#importdatatable_2}

Importerar ett DataTable‑objekt, men inte som en hel enhet. Endast angivna rader och kolumner importeras.

```csharp
public void ImportDataTable(DataTable importedDataTable, int[] sourceRowList, 
    int[] sourceColumnList, int firstFilledRow, int firstFilledColumn, 
    bool showColumnNamesAsFirstRow, bool isHtmlSupported = false)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| importedDataTable | DataTable | DataTable-objektet som ska importeras. |
| sourceRowList | Int32[] | Arrayen med radnummer i käll-DataTable-objektet som måste importeras. Listan får inte vara null och får endast innehålla nummer på befintliga rader, annars kastas ett undantag. |
| sourceColumnList | Int32[] | Arrayen med kolumnnummer i käll‑DataTable‑objektet som måste importeras. Listan får inte vara null och får endast innehålla nummer på befintliga kolumner, annars kastas ett undantag. |
| firstFilledRow | Int32 | Det nollbaserade radnumret för den första cellen i mål‑tabellen där importen ska börja. Om mål‑tabellen inte innehåller den raden skapas den (och alla föregående vid behov). |
| firstFilledColumn | Int32 | Det nollbaserade kolumnnumret för den första cellen i mål‑tabellen där importen ska börja. Mål‑tabellen måste innehålla den kolumnen innan importen startar, annars kastas ett undantag. |
| showColumnNamesAsFirstRow | Boolean | Anger om kolumnnamnen i källdatatabellen ska importeras som första rad. |
| isHtmlSupported | Boolean | Anger om texten är en HTML-sträng. |

### Se även

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


