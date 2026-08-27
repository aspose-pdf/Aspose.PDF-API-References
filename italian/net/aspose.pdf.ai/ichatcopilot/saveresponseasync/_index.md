---
title: "IChatCopilot.SaveResponseAsync"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo IChatCopilot. Salva in modo asincrono la risposta per il messaggio fornito in un file PDF"
type: docs
weight: 40
url: /it/net/aspose.pdf.ai/ichatcopilot/saveresponseasync/
---
## SaveResponseAsync(string, string, CancellationToken?) {#saveresponseasync_3}

Salva in modo asincrono la risposta per il messaggio fornito in un file PDF.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messaggio | String | Il messaggio di input per il quale la risposta viene salvata. |
| outputFileName | String | Il nome del file PDF di output in cui salvare la risposta. |
| cancellationToken | Nullable`1 | Il token di cancellazione (opzionale). |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona.

### Vedi anche

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(string, string, SaveFormat, CancellationToken?) {#saveresponseasync_2}

Salva in modo asincrono la risposta per il messaggio fornito in un file con il formato specificato.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messaggio | String | Il messaggio di input per il quale la risposta viene salvata. |
| outputFileName | String | Il nome del file di output in cui salvare la risposta. |
| saveFormat | SaveFormat | Il formato in cui salvare la risposta (PDF se non specificato). |
| cancellationToken | Nullable`1 | Il token di cancellazione (opzionale). |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona.

### Vedi anche

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, CancellationToken?) {#saveresponseasync_1}

Salva in modo asincrono le risposte per l'elenco di messaggi fornito in un file PDF.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messaggi | List`1 | L'elenco dei messaggi di input per i quali le risposte vengono salvate. |
| outputFileName | String | Il nome del file PDF di output in cui salvare le risposte. |
| cancellationToken | Nullable`1 | Il token di cancellazione (opzionale). |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona.

### Vedi anche

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, SaveFormat, CancellationToken?) {#saveresponseasync}

Salva in modo asincrono le risposte per l'elenco di messaggi fornito in un file con il formato specificato.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messaggi | List`1 | L'elenco dei messaggi di input per i quali le risposte vengono salvate. |
| outputFileName | String | Il nome del file di output in cui salvare le risposte. |
| saveFormat | SaveFormat | Il formato in cui salvare le risposte (PDF se non specificato). |
| cancellationToken | Nullable`1 | Il token di cancellazione (opzionale). |

### Valore di ritorno

Un'attività che rappresenta l'operazione asincrona.

### Vedi anche

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


