---
title: IChatCopilot.GetResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IChatCopilot. Obtém uma resposta de forma assíncrona para a mensagem dada
type: docs
weight: 20
url: /pt/net/aspose.pdf.ai/ichatcopilot/getresponseasync/
---
## GetResponseAsync(string, CancellationToken?) {#getresponseasync_1}

Obtém uma resposta de forma assíncrona para a mensagem dada.

```csharp
public Task<string> GetResponseAsync(string message, CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| message | String | A mensagem de entrada para a qual uma resposta é solicitada. |
| cancellationToken | Nullable`1 | O token de cancelamento (opcional). |

### Valor de Retorno

Uma tarefa representando a operação assíncrona com a string de resposta.

### Veja Também

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## GetResponseAsync(List&lt;string&gt;, CancellationToken?) {#getresponseasync}

Obtém uma resposta de forma assíncrona para a lista dada de mensagens.

```csharp
public Task<string> GetResponseAsync(List<string> messages, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| messages | List`1 | A lista de mensagens de entrada para as quais as respostas são solicitadas. |
| cancellationToken | Nullable`1 | O token de cancelamento (opcional). |

### Valor de Retorno

Uma tarefa representando a operação assíncrona com a string de resposta.

### Veja Também

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)