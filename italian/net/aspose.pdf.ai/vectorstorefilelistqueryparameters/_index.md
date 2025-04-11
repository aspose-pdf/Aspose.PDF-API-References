---
title: Class VectorStoreFileListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.VectorStoreFileListQueryParameters. Oggetto dei parametri di query per elencare i file del negozio vettoriale
type: docs
weight: 1330
url: /it/net/aspose.pdf.ai/vectorstorefilelistqueryparameters/
---
## Classe VectorStoreFileListQueryParameters

Oggetto dei parametri di query per elencare i file del negozio vettoriale.

```csharp
public class VectorStoreFileListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [VectorStoreFileListQueryParameters](vectorstorefilelistqueryparameters/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Ottiene o imposta un cursore da utilizzare nella paginazione. after è un ID oggetto che definisce la tua posizione nell'elenco. Ad esempio, se fai una richiesta di elenco e ricevi 100 oggetti, terminando con obj_foo, la tua chiamata successiva può includere after=obj_foo per recuperare la pagina successiva dell'elenco. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Ottiene o imposta un cursore da utilizzare nella paginazione. before è un ID oggetto che definisce la tua posizione nell'elenco. Ad esempio, se fai una richiesta di elenco e ricevi 100 oggetti, terminando con obj_foo, la tua chiamata successiva può includere before=obj_foo per recuperare la pagina precedente dell'elenco. |
| [Filter](../../aspose.pdf.ai/vectorstorefilelistqueryparameters/filter/) { get; set; } | Ottiene o imposta un filtro per stato del file. Uno tra in_progress, completed, failed, cancelled. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Ottiene o imposta un limite sul numero di oggetti da restituire. Il limite può variare tra 1 e 100, e il predefinito è 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Ottiene o imposta l'ordine di ordinamento in base al timestamp created_at degli oggetti. asc per ordine crescente e desc per ordine decrescente. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/vectorstorefilelistqueryparameters/getqueryparameters/)() | Ottiene i parametri di query per elencare i file del negozio vettoriale. |

### Vedi Anche

* classe [BaseListQueryParameters](../baselistqueryparameters/)
* interfaccia [IQueryParameters](../iqueryparameters/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)