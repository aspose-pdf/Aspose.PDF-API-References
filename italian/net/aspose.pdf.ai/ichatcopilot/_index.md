---
title: Interface IChatCopilot
second_title: Aspose.PDF for .NET API Reference
description: Interfaccia Aspose.Pdf.AI.IChatCopilot. Rappresenta un copilota di chat per interagire con documenti tramite modelli AI
type: docs
weight: 470
url: /it/net/aspose.pdf.ai/ichatcopilot/
---
## Interfaccia IChatCopilot

Rappresenta un copilota di chat per interagire con documenti tramite modelli AI.

```csharp
public interface IChatCopilot : IAICopilot
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [DeleteContextAsync](../../aspose.pdf.ai/ichatcopilot/deletecontextasync/)(CancellationToken?) | Elimina il contesto in modo asincrono. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync)(List&lt;string&gt;, CancellationToken?) | Ottiene una risposta in modo asincrono per l'elenco di messaggi fornito. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync_1)(string, CancellationToken?) | Ottiene una risposta in modo asincrono per il messaggio fornito. |
| [SaveContextAsync](../../aspose.pdf.ai/ichatcopilot/savecontextasync/)(string, CancellationToken?) | Salva il contesto in modo asincrono in un file JSON. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_1)(List&lt;string&gt;, string, CancellationToken?) | Salva le risposte in modo asincrono per l'elenco di messaggi fornito in un file PDF. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_3)(string, string, CancellationToken?) | Salva la risposta in modo asincrono per il messaggio fornito in un file PDF. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync)(List&lt;string&gt;, string, SaveFormat, CancellationToken?) | Salva le risposte in modo asincrono per l'elenco di messaggi fornito in un file con formato specificato. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_2)(string, string, SaveFormat, CancellationToken?) | Salva la risposta in modo asincrono per il messaggio fornito in un file con formato specificato. |

### Vedi Anche

* interfaccia [IAICopilot](../iaicopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)