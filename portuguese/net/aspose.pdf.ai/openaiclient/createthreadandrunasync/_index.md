---
title: OpenAIClient.CreateThreadAndRunAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Cria uma thread e uma execução dentro dela de forma assíncrona
type: docs
weight: 60
url: /pt/net/aspose.pdf.ai/openaiclient/createthreadandrunasync/
---
## Método OpenAIClient.CreateThreadAndRunAsync

Cria uma thread e uma execução dentro dela de forma assíncrona.

```csharp
public Task<RunResponse> CreateThreadAndRunAsync(RunThreadCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| runCreateRequest | RunThreadCreateRequest | Os detalhes da solicitação para criar a thread e a execução. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém a resposta da criação da thread e da execução.

### Veja Também

* classe [RunResponse](../../runresponse/)
* classe [RunThreadCreateRequest](../../runthreadcreaterequest/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)