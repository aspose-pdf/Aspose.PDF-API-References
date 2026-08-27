---
title: "Classe AssistantListQueryParameters"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.AI.AssistantListQueryParameters classe. Rappresenta l'oggetto dei parametri di query per elencare gli assistenti"
type: docs
weight: 110
url: /it/net/aspose.pdf.ai/assistantlistqueryparameters/
---
## AssistantListQueryParameters class

Rappresenta l'oggetto dei parametri di query per l'elenco degli assistenti.

```csharp
public class AssistantListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [AssistantListQueryParameters](assistantlistqueryparameters/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Ottiene o imposta un cursore da utilizzare nella paginazione. after è un ID oggetto che definisce la tua posizione nella lista. Ad esempio, se effettui una richiesta di elenco e ricevi 100 oggetti, terminanti con obj_foo, la chiamata successiva può includere after=obj_foo per recuperare la pagina successiva della lista. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Ottiene o imposta un cursore da utilizzare nella paginazione. before è un ID oggetto che definisce la tua posizione nella lista. Ad esempio, se effettui una richiesta di elenco e ricevi 100 oggetti, terminanti con obj_foo, la chiamata successiva può includere before=obj_foo per recuperare la pagina precedente della lista. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Ottiene o imposta un limite sul numero di oggetti da restituire. Il limite può variare tra 1 e 100, e il valore predefinito è 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Ottiene o imposta l'ordine di ordinamento in base al timestamp created_at degli oggetti. asc per ordine ascendente e desc per ordine discendente. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/assistantlistqueryparameters/getqueryparameters/)() | Ottiene i parametri di query per elencare gli assistenti. |

### Vedi anche

* class [BaseListQueryParameters](../baselistqueryparameters/)
* interface [IQueryParameters](../iqueryparameters/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


