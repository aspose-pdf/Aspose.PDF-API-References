---
title: Interface IChatCopilot
second_title: Aspose.PDF for .NET API Reference
description: Interface Aspose.Pdf.AI.IChatCopilot. Representa um copiloto de chat para interagir com documentos via modelos de IA
type: docs
weight: 470
url: /pt/net/aspose.pdf.ai/ichatcopilot/
---
## Interface IChatCopilot

Representa um copiloto de chat para interagir com documentos via modelos de IA.

```csharp
public interface IChatCopilot : IAICopilot
```

## Métodos

| Nome | Descrição |
| --- | --- |
| [DeleteContextAsync](../../aspose.pdf.ai/ichatcopilot/deletecontextasync/)(CancellationToken?) | Exclui o contexto de forma assíncrona. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync)(List&lt;string&gt;, CancellationToken?) | Obtém uma resposta de forma assíncrona para a lista de mensagens dada. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync_1)(string, CancellationToken?) | Obtém uma resposta de forma assíncrona para a mensagem dada. |
| [SaveContextAsync](../../aspose.pdf.ai/ichatcopilot/savecontextasync/)(string, CancellationToken?) | Salva o contexto de forma assíncrona em um arquivo JSON. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_1)(List&lt;string&gt;, string, CancellationToken?) | Salva as respostas de forma assíncrona para a lista de mensagens dada em um arquivo PDF. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_3)(string, string, CancellationToken?) | Salva a resposta de forma assíncrona para a mensagem dada em um arquivo PDF. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync)(List&lt;string&gt;, string, SaveFormat, CancellationToken?) | Salva as respostas de forma assíncrona para a lista de mensagens dada em um arquivo com formato especificado. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_2)(string, string, SaveFormat, CancellationToken?) | Salva a resposta de forma assíncrona para a mensagem dada em um arquivo com formato especificado. |

### Veja Também

* interface [IAICopilot](../iaicopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)