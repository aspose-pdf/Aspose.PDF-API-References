---
title: "Classe VectorStoreFileListQueryParameters"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.AI.VectorStoreFileListQueryParameters classe. Oggetto dei parametri di query per l'elenco dei file di vector store"
type: docs
weight: 1420
url: /it/net/aspose.pdf.ai/vectorstorefilelistqueryparameters/
---
## VectorStoreFileListQueryParameters class

Oggetto dei parametri di query per elencare i file del vector store.

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
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Ottiene o imposta un cursore da utilizzare nella paginazione. after è un ID oggetto che definisce la tua posizione nella lista. Ad esempio, se effettui una richiesta di elenco e ricevi 100 oggetti, terminanti con obj_foo, la chiamata successiva può includere after=obj_foo per recuperare la pagina successiva della lista. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Ottiene o imposta un cursore da utilizzare nella paginazione. before è un ID oggetto che definisce la tua posizione nella lista. Ad esempio, se effettui una richiesta di elenco e ricevi 100 oggetti, terminanti con obj_foo, la chiamata successiva può includere before=obj_foo per recuperare la pagina precedente della lista. |
| [Filter](../../aspose.pdf.ai/vectorstorefilelistqueryparameters/filter/) { get; set; } | Ottiene o imposta un filtro per lo stato del file. Uno tra in_progress, completed, failed, cancelled. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Ottiene o imposta un limite sul numero di oggetti da restituire. Il limite può variare tra 1 e 100, e il valore predefinito è 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Ottiene o imposta l'ordine di ordinamento in base al timestamp created_at degli oggetti. asc per ordine ascendente e desc per ordine discendente. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/vectorstorefilelistqueryparameters/getqueryparameters/)() | Ottiene i parametri di query per l'elenco dei file di vector store. |

### Vedi anche

* class [BaseListQueryParameters](../baselistqueryparameters/)
* interface [IQueryParameters](../iqueryparameters/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


