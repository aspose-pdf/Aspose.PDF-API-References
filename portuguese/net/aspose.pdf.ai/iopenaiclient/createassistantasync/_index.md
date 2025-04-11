---
title: IOpenAIClient.CreateAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Cria um novo assistente de forma assíncrona
type: docs
weight: 30
url: /pt/net/aspose.pdf.ai/iopenaiclient/createassistantasync/
---
## Método IOpenAIClient.CreateAssistantAsync

Cria um novo assistente de forma assíncrona.

```csharp
public Task<AssistantResponse> CreateAssistantAsync(AssistantCreateRequest assistantCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| assistantCreateRequest | AssistantCreateRequest | O objeto de solicitação contendo detalhes para criar o assistente. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém a resposta da criação do assistente.

### Veja Também

* classe [AssistantResponse](../../assistantresponse/)
* classe [AssistantCreateRequest](../../assistantcreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)