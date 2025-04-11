---
title: IOpenAIClient.RunAndGetAssistantResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Executa o assistente com o threadId especificado e runCreateRequest e obtém a resposta do assistente de forma assíncrona
type: docs
weight: 410
url: /pt/net/aspose.pdf.ai/iopenaiclient/runandgetassistantresponseasync/
---
## Método IOpenAIClient.RunAndGetAssistantResponseAsync

Executa o assistente com o threadId especificado e runCreateRequest, e obtém a resposta do assistente de forma assíncrona.

```csharp
public Task<string> RunAndGetAssistantResponseAsync(string threadId, 
    RunCreateRequest runCreateRequest, CancellationToken? cancellationToken)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| threadId | String | O ID do thread. |
| runCreateRequest | RunCreateRequest | A solicitação de criação de execução. |
| cancellationToken | Nullable`1 | O token de cancelamento (opcional). |

### Valor de Retorno

Uma tarefa representando a operação assíncrona com a string de resposta do assistente.

### Veja Também

* classe [RunCreateRequest](../../runcreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)