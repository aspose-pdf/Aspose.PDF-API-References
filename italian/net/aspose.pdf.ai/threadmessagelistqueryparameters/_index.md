---
title: "Classe ThreadMessageListQueryParameters"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.AI.ThreadMessageListQueryParameters classe. Oggetto dei parametri di query per elencare i messaggi del thread"
type: docs
weight: 1220
url: /it/net/aspose.pdf.ai/threadmessagelistqueryparameters/
---
## ThreadMessageListQueryParameters class

Oggetto dei parametri di query per elencare i messaggi del thread.

```csharp
public class ThreadMessageListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ThreadMessageListQueryParameters](threadmessagelistqueryparameters/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Ottiene o imposta un cursore da utilizzare nella paginazione. after è un ID oggetto che definisce la tua posizione nella lista. Ad esempio, se effettui una richiesta di elenco e ricevi 100 oggetti, terminanti con obj_foo, la chiamata successiva può includere after=obj_foo per recuperare la pagina successiva della lista. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Ottiene o imposta un cursore da utilizzare nella paginazione. before è un ID oggetto che definisce la tua posizione nella lista. Ad esempio, se effettui una richiesta di elenco e ricevi 100 oggetti, terminanti con obj_foo, la chiamata successiva può includere before=obj_foo per recuperare la pagina precedente della lista. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Ottiene o imposta un limite sul numero di oggetti da restituire. Il limite può variare tra 1 e 100, e il valore predefinito è 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Ottiene o imposta l'ordine di ordinamento in base al timestamp created_at degli oggetti. asc per ordine ascendente e desc per ordine discendente. |
| [RunId](../../aspose.pdf.ai/threadmessagelistqueryparameters/runid/) { get; set; } | Filtra i messaggi per ID di esecuzione che li ha generati. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/threadmessagelistqueryparameters/getqueryparameters/)() | Ottiene i parametri di query per elencare i messaggi del thread. |

### Vedi anche

* class [BaseListQueryParameters](../baselistqueryparameters/)
* interface [IQueryParameters](../iqueryparameters/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


