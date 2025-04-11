---
title: IOpenAIClient.ModifyAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Modifica um assistente existente de forma assíncrona
type: docs
weight: 360
url: /pt/net/aspose.pdf.ai/iopenaiclient/modifyassistantasync/
---
## Método IOpenAIClient.ModifyAssistantAsync

Modifica um assistente existente de forma assíncrona.

```csharp
public Task<AssistantResponse> ModifyAssistantAsync(string assistantId, 
    AssistantModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| assistantId | String | O ID do assistente a ser modificado. |
| assistantModifyRequest | AssistantModifyRequest | O objeto de solicitação contendo os detalhes da modificação. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém a resposta da modificação do assistente.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do assistente é nulo ou vazio. |

### Veja Também

* classe [AssistantResponse](../../assistantresponse/)
* classe [AssistantModifyRequest](../../assistantmodifyrequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)