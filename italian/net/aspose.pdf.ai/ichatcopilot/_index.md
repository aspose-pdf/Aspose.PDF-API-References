---
title: "Interfaccia IChatCopilot"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Interfaccia Aspose.Pdf.AI.IChatCopilot. Rappresenta un copilot di chat per interagire con i documenti tramite modelli AI"
type: docs
weight: 490
url: /it/net/aspose.pdf.ai/ichatcopilot/
---
## IChatCopilot interface

Rappresenta un copilota di chat per interagire con i documenti tramite modelli AI.

```csharp
public interface IChatCopilot : IAICopilot
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [DeleteContextAsync](../../aspose.pdf.ai/ichatcopilot/deletecontextasync/)(CancellationToken?) | Elimina in modo asincrono il contesto. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync)(List&lt;string&gt;, CancellationToken?) | Ottiene in modo asincrono una risposta per l'elenco di messaggi fornito. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync_1)(string, CancellationToken?) | Ottiene in modo asincrono una risposta per il messaggio fornito. |
| [SaveContextAsync](../../aspose.pdf.ai/ichatcopilot/savecontextasync/)(string, CancellationToken?) | Salva in modo asincrono il contesto in un file JSON. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_1)(List&lt;string&gt;, string, CancellationToken?) | Salva in modo asincrono le risposte per l'elenco di messaggi fornito in un file PDF. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_3)(string, string, CancellationToken?) | Salva in modo asincrono la risposta per il messaggio fornito in un file PDF. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync)(List&lt;string&gt;, string, SaveFormat, CancellationToken?) | Salva in modo asincrono le risposte per l'elenco di messaggi fornito in un file con il formato specificato. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_2)(string, string, SaveFormat, CancellationToken?) | Salva in modo asincrono la risposta per il messaggio fornito in un file con il formato specificato. |

### Vedi anche

* interface [IAICopilot](../iaicopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


