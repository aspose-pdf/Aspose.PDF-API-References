---
title: OpenAIClient.WaitForVectorStoreToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Aguarda que um armazenamento de vetores específico seja concluído assíncronamente
type: docs
weight: 500
url: /pt/net/aspose.pdf.ai/openaiclient/waitforvectorstoretocompleteasync/
---
## Método OpenAIClient.WaitForVectorStoreToCompleteAsync

Aguarda que um armazenamento de vetores específico seja concluído assíncronamente.

```csharp
public Task<VectorStoreResponse> WaitForVectorStoreToCompleteAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| vectorStoreId | String | O ID do armazenamento de vetores a ser monitorado até a conclusão. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém o status final do armazenamento de vetores.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do armazenamento de vetores é nulo ou vazio. |

### Veja Também

* classe [VectorStoreResponse](../../vectorstoreresponse/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)