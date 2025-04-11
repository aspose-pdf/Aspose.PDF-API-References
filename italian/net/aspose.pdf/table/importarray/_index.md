---
title: Table.ImportArray
second_title: Aspose.PDF for .NET API Reference
description: Metodo della tabella. Importa un array unidimensionale di dati nella tabella. L'importazione avviene una cella per ogni elemento dell'array e inizia dalla riga e dalla colonna definite nei parametri. Durante l'importazione, se viene rilevato che le righe necessarie sono ancora assenti, cioè la tabella di destinazione è troppo piccola per assorbire tutti i dati, verranno create le righe necessarie.
type: docs
weight: 250
url: /it/net/aspose.pdf/table/importarray/
---
## Metodo Table.ImportArray

Importa un array unidimensionale di dati nella tabella. L'importazione avviene una cella per ogni elemento dell'array e inizia dalla riga e dalla colonna definite nei parametri. Durante l'importazione, se viene rilevato che le righe necessarie sono ancora assenti (cioè la tabella di destinazione è troppo piccola per assorbire tutti i dati), verranno create le righe necessarie.

```csharp
public void ImportArray(object[] importedArray, int firstFilledRow, int firstFilledColumn, 
    bool isLeftColumnsFilled)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| importedArray | Object[] | dati importati, i null verranno importati come stringhe vuote |
| firstFilledRow | Int32 | definisce il numero della prima riga di destinazione nella tabella di destinazione da cui inizierà l'importazione. Se il numero di righe nella tabella di destinazione è inferiore a quello richiesto, le righe mancanti verranno create per prime. |
| firstFilledColumn | Int32 | specifica il numero della prima colonna di destinazione nella tabella di destinazione, la colonna deve essere presente nella tabella di destinazione prima dell'inizio dell'importazione |
| isLeftColumnsFilled | Boolean | Se 'isLeftColumnsFilled'=false, allora nelle righe riempite successive, le celle a sinistra della firstFilledColumn verranno saltate |

### Vedi Anche

* classe [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)