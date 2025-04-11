---
title: IOpenAIClient.WaitForVectorStoreFileToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Aguarda que um arquivo específico do armazenamento vetorial seja concluído assíncronamente
type: docs
weight: 460
url: /pt/net/aspose.pdf.ai/iopenaiclient/waitforvectorstorefiletocompleteasync/
---
## Método IOpenAIClient.WaitForVectorStoreFileToCompleteAsync

Aguarda que um arquivo específico do armazenamento vetorial seja concluído assíncronamente.

```csharp
public Task<VectorStoreFileResponse> WaitForVectorStoreFileToCompleteAsync(string vectorStoreId, 
    string fileId, CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| vectorStoreId | String | O ID do armazenamento vetorial que contém o arquivo. |
| fileId | String | O ID do arquivo a ser monitorado até a conclusão. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém o status final do arquivo.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do armazenamento vetorial é nulo ou vazio. |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do arquivo é nulo ou vazio. |

### Veja Também

* classe [VectorStoreFileResponse](../../vectorstorefileresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)