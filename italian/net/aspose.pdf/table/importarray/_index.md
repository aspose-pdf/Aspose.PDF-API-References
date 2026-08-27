---
title: "Table.ImportArray"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo della classe Table. Importa un array monodimensionale di dati nella tabella. L'importazione inserisce una cella per ogni elemento dell'array e inizia dalla riga e colonna definite nei parametri. Durante l'importazione, se si rileva che le righe necessarie sono ancora assenti, ad esempio la tabella di destinazione è troppo piccola per contenere tutti i dati, verranno create le righe necessarie"
type: docs
weight: 250
url: /it/net/aspose.pdf/table/importarray/
---
## Table.ImportArray method

Importa un array unidimensionale di dati nella tabella. L'importazione inserisce una cella per ogni elemento dell'array e inizia dalla riga e colonna definite nei parametri. Durante l'importazione, se viene rilevato che le righe necessarie sono ancora assenti (ad esempio la tabella di destinazione è troppo piccola per contenere tutti i dati), le righe necessarie verranno create.

```csharp
public void ImportArray(object[] importedArray, int firstFilledRow, int firstFilledColumn, 
    bool isLeftColumnsFilled)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| importedArray | Object[] | dati importati, i valori null saranno importati come stringhe vuote |
| firstFilledRow | Int32 | Definisce il numero della prima riga di destinazione nella tabella di destinazione da cui inizierà l'importazione. Se il numero di righe nella tabella di destinazione è inferiore a quello richiesto, le righe mancanti saranno create per prime. |
| firstFilledColumn | Int32 | specifica il numero della prima colonna di destinazione nella tabella di destinazione, la colonna deve essere presente nella tabella di destinazione prima dell'inizio dell'importazione |
| isLeftColumnsFilled | Boolean | Se 'isLeftColumnsFilled'=false, allora nella seconda e in tutte le righe successive riempite le celle che si trovano a sinistra di firstFilledColumn saranno ignorate |

### Vedi anche

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


