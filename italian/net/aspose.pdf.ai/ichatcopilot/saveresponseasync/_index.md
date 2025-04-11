---
title: IChatCopilot.SaveResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: Metodo IChatCopilot. Salva in modo asincrono la risposta per il messaggio dato in un file PDF
type: docs
weight: 40
url: /it/net/aspose.pdf.ai/ichatcopilot/saveresponseasync/
---
## SaveResponseAsync(string, string, CancellationToken?) {#saveresponseasync_3}

Salva in modo asincrono la risposta per il messaggio dato in un file PDF.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | String | Il messaggio di input per il quale viene salvata la risposta. |
| outputFileName | String | Il nome del file PDF di output in cui salvare la risposta. |
| cancellationToken | Nullable`1 | Il token di cancellazione (opzionale). |

### Return Value

Un'attività che rappresenta l'operazione asincrona.

### See Also

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(string, string, SaveFormat, CancellationToken?) {#saveresponseasync_2}

Salva in modo asincrono la risposta per il messaggio dato in un file con formato specificato.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | String | Il messaggio di input per il quale viene salvata la risposta. |
| outputFileName | String | Il nome del file di output in cui salvare la risposta. |
| saveFormat | SaveFormat | Il formato in cui salvare la risposta (PDF se non specificato). |
| cancellationToken | Nullable`1 | Il token di cancellazione (opzionale). |

### Return Value

Un'attività che rappresenta l'operazione asincrona.

### See Also

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, CancellationToken?) {#saveresponseasync_1}

Salva in modo asincrono le risposte per l'elenco dato di messaggi in un file PDF.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messages | List`1 | L'elenco dei messaggi di input per i quali vengono salvate le risposte. |
| outputFileName | String | Il nome del file PDF di output in cui salvare le risposte. |
| cancellationToken | Nullable`1 | Il token di cancellazione (opzionale). |

### Return Value

Un'attività che rappresenta l'operazione asincrona.

### See Also

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, SaveFormat, CancellationToken?) {#saveresponseasync}

Salva in modo asincrono le risposte per l'elenco dato di messaggi in un file con formato specificato.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messages | List`1 | L'elenco dei messaggi di input per i quali vengono salvate le risposte. |
| outputFileName | String | Il nome del file di output in cui salvare le risposte. |
| saveFormat | SaveFormat | Il formato in cui salvare le risposte (PDF se non specificato). |
| cancellationToken | Nullable`1 | Il token di cancellazione (opzionale). |

### Return Value

Un'attività che rappresenta l'operazione asincrona.

### See Also

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)