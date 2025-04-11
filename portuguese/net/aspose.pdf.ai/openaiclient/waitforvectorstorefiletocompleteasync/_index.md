---
title: OpenAIClient.WaitForVectorStoreFileToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: Método OpenAIClient. Aguarda que um arquivo específico do vetor de armazenamento seja concluído assíncronamente
type: docs
weight: 490
url: /pt/net/aspose.pdf.ai/openaiclient/waitforvectorstorefiletocompleteasync/
---
## Método OpenAIClient.WaitForVectorStoreFileToCompleteAsync

Aguarda que um arquivo específico do vetor de armazenamento seja concluído assíncronamente.

```csharp
public Task<VectorStoreFileResponse> WaitForVectorStoreFileToCompleteAsync(string vectorStoreId, 
    string fileId, CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| vectorStoreId | String | O ID do vetor de armazenamento que contém o arquivo. |
| fileId | String | O ID do arquivo a ser monitorado até a conclusão. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém o status final do arquivo.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do vetor de armazenamento é nulo ou vazio. |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do arquivo é nulo ou vazio. |

### Veja Também

* classe [VectorStoreFileResponse](../../vectorstorefileresponse/)
* classe [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)