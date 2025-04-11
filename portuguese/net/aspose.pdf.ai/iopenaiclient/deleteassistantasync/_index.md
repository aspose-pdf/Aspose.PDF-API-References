---
title: IOpenAIClient.DeleteAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Exclui um assistente existente de forma assíncrona
type: docs
weight: 130
url: /pt/net/aspose.pdf.ai/iopenaiclient/deleteassistantasync/
---
## Método IOpenAIClient.DeleteAssistantAsync

Exclui um assistente existente de forma assíncrona.

```csharp
public Task<DeleteStatusResponse> DeleteAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| assistantId | String | O ID do assistente a ser excluído. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém o status da operação de exclusão.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do assistente é nulo ou vazio. |

### Veja Também

* classe [DeleteStatusResponse](../../deletestatusresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)