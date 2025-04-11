---
title: IChatCopilot.GetResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo IChatCopilot. Ottiene in modo asincrono una risposta per il messaggio fornito
type: docs
weight: 20
url: /it/net/aspose.pdf.ai/ichatcopilot/getresponseasync/
---
## GetResponseAsync(string, CancellationToken?) {#getresponseasync_1}

Ottiene in modo asincrono una risposta per il messaggio fornito.

```csharp
public Task<string> GetResponseAsync(string message, CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | String | Il messaggio di input per il quale è richiesta una risposta. |
| cancellationToken | Nullable`1 | Il token di cancellazione (opzionale). |

### Return Value

Un'attività che rappresenta l'operazione asincrona con la stringa di risposta.

### See Also

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## GetResponseAsync(List&lt;string&gt;, CancellationToken?) {#getresponseasync}

Ottiene in modo asincrono una risposta per l'elenco fornito di messaggi.

```csharp
public Task<string> GetResponseAsync(List<string> messages, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messages | List`1 | L'elenco dei messaggi di input per i quali sono richieste risposte. |
| cancellationToken | Nullable`1 | Il token di cancellazione (opzionale). |

### Return Value

Un'attività che rappresenta l'operazione asincrona con la stringa di risposta.

### See Also

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)