---
title: Class VectorStoreListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.VectorStoreListQueryParameters classe. Parametri di query oggetto per elencare archivi vettoriali.
type: docs
weight: 1360
url: /it/net/aspose.pdf.ai/vectorstorelistqueryparameters/
---
## Classe VectorStoreListQueryParameters

Oggetto dei parametri di query per l'elenco dei negozi di vettori.

```csharp
public class VectorStoreListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [VectorStoreListQueryParameters](vectorstorelistqueryparameters/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Ottiene o imposta un cursore da utilizzare nella paginazione. after è un ID oggetto che definisce la tua posizione nell'elenco. Ad esempio, se fai una richiesta di elenco e ricevi 100 oggetti, terminando con obj_foo, la tua chiamata successiva può includere after=obj_foo per recuperare la pagina successiva dell'elenco. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Ottiene o imposta un cursore da utilizzare nella paginazione. before è un ID oggetto che definisce la tua posizione nell'elenco. Ad esempio, se fai una richiesta di elenco e ricevi 100 oggetti, terminando con obj_foo, la tua chiamata successiva può includere before=obj_foo per recuperare la pagina precedente dell'elenco. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Ottiene o imposta un limite sul numero di oggetti da restituire. Limit può variare tra 1 e 100, e il valore predefinito è 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Ottiene o imposta l'ordine di ordinamento in base al timestamp created_at degli oggetti. asc per ordine crescente e desc per ordine decrescente. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/vectorstorelistqueryparameters/getqueryparameters/)() | Ottiene i parametri di query per l'elenco dei negozi di vettori. |

### Vedi Anche

* classe [BaseListQueryParameters](../baselistqueryparameters/)
* interfaccia [IQueryParameters](../iqueryparameters/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)