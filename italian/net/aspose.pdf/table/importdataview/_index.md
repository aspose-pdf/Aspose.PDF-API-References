---
title: "Table.ImportDataView"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Table. Importa i dati di un oggetto DataView nella tabella"
type: docs
weight: 270
url: /it/net/aspose.pdf/table/importdataview/
---
## Table.ImportDataView method

Importa i dati di un oggetto DataView nella tabella.

```csharp
public void ImportDataView(DataView sourceDataView, bool isColumnNamesImported, int firstFilledRow, 
    int firstFilledColumn, int maxRows, int maxColumns)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceDataView | DataView | L'oggetto DataView da importare. |
| isColumnNamesImported | Boolean | Indica se i nomi delle colonne saranno importati come prima riga. |
| firstFilledRow | Int32 | Il numero di riga basato su zero della prima cella nella tabella di destinazione da cui inizierà l'importazione. Se la tabella di destinazione non contiene quella riga, essa (e tutte le precedenti, se necessario) verrà creata. |
| firstFilledColumn | Int32 | Il numero della colonna, basato su zero, della prima cella nella tabella di destinazione da cui iniziare l'importazione. La tabella di destinazione deve contenere quella colonna prima dell'inizio dell'importazione, altrimenti verrà generata un'eccezione. |
| maxRows | Int32 | Numero massimo di righe da importare dal DataView di origine. |
| maxColumns | Int32 | Numero massimo di colonne da importare dal DataView di origine. |

### Vedi anche

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


