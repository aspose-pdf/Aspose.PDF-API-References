---
title: "Table.ImportDataTable"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Table. Importa dati da System.Data.DataTable in Aspose.Pdf.Table"
type: docs
weight: 260
url: /it/net/aspose.pdf/table/importdatatable/
---
## ImportDataTable(DataTable, bool, int, int) {#importdatatable_1}

Importa dati da System.Data.DataTable in Aspose.Pdf.Table.

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesImported, 
    int firstFilledRow, int firstFilledColumn)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| importedDataTable | DataTable | istanza di origine di System.Data.DataTable |
| isColumnNamesImported | Boolean | specifica se i nomi delle colonne saranno importati come prima riga |
| firstFilledRow | Int32 | specifica il numero basato su zero della prima riga nella tabella di destinazione da cui iniziare l'importazione; se la riga con tale numero (e alcune righe precedenti) sono assenti nella tabella di destinazione, verranno create prima |
| firstFilledColumn | Int32 | specifica il numero della prima colonna di destinazione nella tabella di destinazione, la colonna deve essere presente nella tabella di destinazione prima dell'inizio dell'importazione |

### Vedi anche

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, bool, int, byte, int, int, bool) {#importdatatable}

Importa un oggetto DataTable nella tabella.

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesShown, 
    int firstFilledRow, byte firstFilledColumn, int maxRows, int maxColumns, 
    bool isHtmlSupported = false)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| importedDataTable | DataTable | L'oggetto DataTable da importare. |
| isColumnNamesShown | Boolean | Specifica se i nomi delle colonne della datatable di origine saranno importati come prima riga. |
| firstFilledRow | Int32 | specifica il numero basato su zero della prima riga nella tabella di destinazione da cui iniziare l'importazione; se la riga con tale numero (e alcune righe precedenti) sono assenti nella tabella di destinazione, verranno create prima |
| firstFilledColumn | Byte | specifica il numero della prima colonna di destinazione nella tabella di destinazione, la colonna deve essere presente nella tabella di destinazione prima dell'inizio dell'importazione |
| maxRows | Int32 | Numero massimo di righe da importare dalla tabella di origine. |
| maxColumns | Int32 | Numero massimo di colonne da importare dalla tabella di origine. |
| isHtmlSupported | Boolean | Specifica se il testo è una stringa HTML. |

### Vedi anche

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, int[], int[], int, int, bool, bool) {#importdatatable_2}

Importa un oggetto DataTable, ma non come entità intera. Solo le righe e le colonne specificate vengono importate.

```csharp
public void ImportDataTable(DataTable importedDataTable, int[] sourceRowList, 
    int[] sourceColumnList, int firstFilledRow, int firstFilledColumn, 
    bool showColumnNamesAsFirstRow, bool isHtmlSupported = false)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| importedDataTable | DataTable | L'oggetto DataTable da importare. |
| sourceRowList | Int32[] | L'array di numeri di righe nell'oggetto DataTable di origine che devono essere importate. L'elenco non deve essere nullo e deve contenere solo numeri di righe esistenti, altrimenti verrà generata un'eccezione. |
| sourceColumnList | Int32[] | L'array di numeri di colonne nell'oggetto DataTable di origine che devono essere importate. L'elenco non deve essere nullo e deve contenere solo numeri di colonne esistenti, altrimenti verrà generata un'eccezione. |
| firstFilledRow | Int32 | Il numero di riga basato su zero della prima cella nella tabella di destinazione da cui inizierà l'importazione. Se la tabella di destinazione non contiene quella riga, essa (e tutte le precedenti, se necessario) verrà creata. |
| firstFilledColumn | Int32 | Il numero di colonna basato su zero della prima cella nella tabella di destinazione da cui inizierà l'importazione. La tabella di destinazione deve contenere quella colonna prima dell'inizio dell'importazione, altrimenti verrà generata un'eccezione. |
| showColumnNamesAsFirstRow | Boolean | Specifica se i nomi delle colonne della datatable di origine saranno importati come prima riga. |
| isHtmlSupported | Boolean | Specifica se il testo è una stringa HTML. |

### Vedi anche

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


