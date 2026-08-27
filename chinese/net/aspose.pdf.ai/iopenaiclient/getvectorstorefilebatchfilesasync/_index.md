---
title: "IOpenAIClient.GetVectorStoreFileBatchFilesAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "IOpenAIClient 方法。异步检索特定向量存储文件批次中的文件列表"
type: docs
weight: 330
url: /zh/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchfilesasync/
---
## IOpenAIClient.GetVectorStoreFileBatchFilesAsync method

异步检索特定向量存储文件批次中的文件列表。

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFileBatchFilesAsync(string vectorStoreId, 
    string fileBatchId, VectorStoreFileBatchFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vectorStoreId | String | 包含该文件批次的向量存储的 ID。 |
| fileBatchId | String | 要检索文件的文件批次的 ID。 |
| queryParameters | VectorStoreFileBatchFileListQueryParameters | 用于过滤文件列表的可选查询参数。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含文件批次中的文件列表。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当向量存储 Id 为 null 或为空时抛出。 |
| [AIClientException](../../aiclientexception/) | 当向量存储文件批次 Id 为 null 或为空时抛出。 |

### 另请参见

* class [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* class [VectorStoreFileBatchFileListQueryParameters](../../vectorstorefilebatchfilelistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


