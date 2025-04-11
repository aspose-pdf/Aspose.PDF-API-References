---
title: Class ThreadResponse
second_title: Aspose.PDF for .NET API Reference
description: Rappresenta un thread che contiene messaggi.
type: docs
weight: 1180
url: /it/net/aspose.pdf.ai/threadresponse/
---
## Classe ThreadResponse

Rappresenta un thread che contiene messaggi.

```csharp
public class ThreadResponse : BaseResponse
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ThreadResponse](threadresponse/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/threadresponse/createdat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando è stato creato il thread. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Ottiene o imposta i dettagli della risposta. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Ottiene o imposta l'errore della risposta HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Ottiene o imposta le informazioni sull'errore. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Ottiene o imposta le intestazioni della risposta HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Ottiene o imposta il codice di stato HTTP. |
| [Id](../../aspose.pdf.ai/threadresponse/id/) { get; set; } | Ottiene o imposta l'identificatore, che può essere referenziato negli endpoint API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indica se la risposta è stata positiva. |
| [Metadata](../../aspose.pdf.ai/threadresponse/metadata/) { get; set; } | Ottiene o imposta un insieme di 16 coppie chiave-valore che possono essere collegate a un oggetto. Questo può essere utile per memorizzare informazioni aggiuntive sull'oggetto in un formato strutturato. Le chiavi possono avere una lunghezza massima di 64 caratteri e i valori possono avere una lunghezza massima di 512 caratteri. |
| [Object](../../aspose.pdf.ai/threadresponse/object/) { get; set; } | Ottiene o imposta il tipo di oggetto, che è sempre thread. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Ottiene la frase di motivo dell'errore. |
| [ToolResources](../../aspose.pdf.ai/threadresponse/toolresources/) { get; set; } | Ottiene o imposta un insieme di risorse che sono rese disponibili agli strumenti dell'assistente in questo thread. Le risorse sono specifiche per il tipo di strumento. Ad esempio, lo strumento code_interpreter richiede un elenco di ID file, mentre lo strumento file_search richiede un elenco di ID di archiviazione vettoriale. |

### Vedi Anche

* classe [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)