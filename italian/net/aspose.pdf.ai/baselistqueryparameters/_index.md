---
title: Class BaseListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.BaseListQueryParameters classe. Parametri di query base per elencare oggetti.
type: docs
weight: 160
url: /it/net/aspose.pdf.ai/baselistqueryparameters/
---
## Classe BaseListQueryParameters

Parametri di query di base per elencare oggetti.

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
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Ottiene o imposta un cursore da utilizzare nella paginazione. after è un ID oggetto che definisce la tua posizione nell'elenco. Ad esempio, se effettui una richiesta di elenco e ricevi 100 oggetti, terminando con obj_foo, la tua chiamata successiva può includere after=obj_foo per recuperare la pagina successiva dell'elenco. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Ottiene o imposta un cursore da utilizzare nella paginazione. before è un ID oggetto che definisce la tua posizione nell'elenco. Ad esempio, se effettui una richiesta di elenco e ricevi 100 oggetti, terminando con obj_foo, la tua chiamata successiva può includere before=obj_foo per recuperare la pagina precedente dell'elenco. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Ottiene o imposta un limite sul numero di oggetti da restituire. Limit può variare tra 1 e 100, e il valore predefinito è 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Ottiene o imposta l'ordine di ordinamento in base al timestamp created_at degli oggetti. asc per ordine crescente e desc per ordine decrescente. |

### Vedi Anche

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)