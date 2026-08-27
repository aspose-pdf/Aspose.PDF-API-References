---
title: "Classe FileResponse"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.AI.FileResponse. L'oggetto FileResponse rappresenta un documento caricato su OpenAI"
type: docs
weight: 420
url: /it/net/aspose.pdf.ai/fileresponse/
---
## FileResponse class

L'oggetto FileResponse rappresenta un documento che è stato caricato su OpenAI.

```csharp
public class FileResponse : BaseResponse, IEntityId
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [FileResponse](fileresponse/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Bytes](../../aspose.pdf.ai/fileresponse/bytes/) { get; set; } | Ottiene o imposta la dimensione del file, in byte. |
| [CreatedAt](../../aspose.pdf.ai/fileresponse/createdat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando il file è stato creato. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Ottiene o imposta il dettaglio della risposta. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Ottiene o imposta l'errore della risposta HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Ottiene o imposta le informazioni sull'errore. |
| [Filename](../../aspose.pdf.ai/fileresponse/filename/) { get; set; } | Ottiene o imposta il nome del file. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Ottiene o imposta le intestazioni della risposta HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Ottiene o imposta il codice di stato HTTP. |
| [Id](../../aspose.pdf.ai/fileresponse/id/) { get; set; } | Ottiene o imposta l'identificatore del file, che può essere referenziato negli endpoint API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indica se la risposta ha avuto successo. |
| [Object](../../aspose.pdf.ai/fileresponse/object/) { get; set; } | Ottiene o imposta il tipo di oggetto, che è sempre file. |
| [Purpose](../../aspose.pdf.ai/fileresponse/purpose/) { get; set; } | Ottiene o imposta lo scopo previsto del file. I valori supportati sono assistants, assistants_output, batch, batch_output, fine-tune, fine-tune-results e vision. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Ottiene la frase di motivo dell'errore. |

### Vedi anche

* class [BaseResponse](../baseresponse/)
* interface [IEntityId](../ientityid/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


