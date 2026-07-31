---
title: "OpenAIClient.CreateRunAsync"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo OpenAIClient. Crea un run all'interno di un thread specificato in modo asincrono"
type: docs
weight: 50
url: /it/net/aspose.pdf.ai/openaiclient/createrunasync/
---
## OpenAIClient.CreateRunAsync method

Crea un run all'interno di un thread specificato in modo asincrono.

```csharp
public Task<RunResponse> CreateRunAsync(string threadId, RunCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threadId | String | L'ID del thread in cui verrà creato il run. |
| runCreateRequest | RunCreateRequest | I dettagli della richiesta per creare il run. |
| cancellationToken | Nullable`1 | Un token per annullare l'operazione. |

### Valore di ritorno

Un task che rappresenta l'operazione asincrona. Il risultato del task contiene la risposta dalla creazione del run.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Generato quando l'ID del thread è nullo o vuoto. |

### Vedi anche

* class [RunResponse](../../runresponse/)
* class [RunCreateRequest](../../runcreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


