---
title: "Classe RunListQueryParameters"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.AI.RunListQueryParameters. Oggetto dei parametri di query per elencare le esecuzioni"
type: docs
weight: 1070
url: /it/net/aspose.pdf.ai/runlistqueryparameters/
---
## RunListQueryParameters class

Oggetto dei parametri di query per elencare le esecuzioni.

```csharp
public class RunListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [RunListQueryParameters](runlistqueryparameters/)() | Il costruttore predefinito. |

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
| [GetQueryParameters](../../aspose.pdf.ai/runlistqueryparameters/getqueryparameters/)() | Ottiene i parametri di query per elencare le esecuzioni. |

### Vedi anche

* class [BaseListQueryParameters](../baselistqueryparameters/)
* interface [IQueryParameters](../iqueryparameters/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


