---
title: IOpenAIClient.CreateVectorStoreFileAsync
second_title: Aspose.PDF for .NET API Reference
description: Método IOpenAIClient. Cria um novo arquivo de armazenamento vetorial de forma assíncrona
type: docs
weight: 110
url: /pt/net/aspose.pdf.ai/iopenaiclient/createvectorstorefileasync/
---
## Método IOpenAIClient.CreateVectorStoreFileAsync

Cria um novo arquivo de armazenamento vetorial de forma assíncrona.

```csharp
public Task<VectorStoreFileResponse> CreateVectorStoreFileAsync(string vectorStoreId, 
    VectorStoreFileCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| vectorStoreId | String | O ID do armazenamento vetorial onde o arquivo será criado. |
| vectorStoreFileCreateRequest | VectorStoreFileCreateRequest | O objeto de solicitação contendo detalhes para a criação do arquivo. |
| cancellationToken | Nullable`1 | Um token para cancelar a operação. |

### Valor de Retorno

Uma tarefa que representa a operação assíncrona. O resultado da tarefa contém a resposta da criação do arquivo.

### Exceções

| exceção | condição |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lançada quando o ID do armazenamento vetorial é nulo ou vazio. |

### Veja Também

* classe [VectorStoreFileResponse](../../vectorstorefileresponse/)
* classe [VectorStoreFileCreateRequest](../../vectorstorefilecreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)