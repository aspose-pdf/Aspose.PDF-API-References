---
title: "Classe BaseListQueryParameters"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.AI.BaseListQueryParameters. Parametri di query di base per elencare gli oggetti"
type: docs
weight: 160
url: /it/net/aspose.pdf.ai/baselistqueryparameters/
---
## BaseListQueryParameters class

Parametri di query di base per l'elenco degli oggetti.

```csharp
public class BaseListQueryParameters
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [BaseListQueryParameters](baselistqueryparameters/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Ottiene o imposta un cursore da utilizzare nella paginazione. after è un ID oggetto che definisce la tua posizione nella lista. Ad esempio, se effettui una richiesta di elenco e ricevi 100 oggetti, terminanti con obj_foo, la chiamata successiva può includere after=obj_foo per recuperare la pagina successiva della lista. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Ottiene o imposta un cursore da utilizzare nella paginazione. before è un ID oggetto che definisce la tua posizione nella lista. Ad esempio, se effettui una richiesta di elenco e ricevi 100 oggetti, terminanti con obj_foo, la chiamata successiva può includere before=obj_foo per recuperare la pagina precedente della lista. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Ottiene o imposta un limite sul numero di oggetti da restituire. Il limite può variare tra 1 e 100, e il valore predefinito è 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Ottiene o imposta l'ordine di ordinamento in base al timestamp created_at degli oggetti. asc per ordine ascendente e desc per ordine discendente. |

### Vedi anche

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


