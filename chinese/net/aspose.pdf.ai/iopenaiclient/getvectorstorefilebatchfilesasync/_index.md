---
title: IOpenAIClient.GetVectorStoreFileBatchFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient 方法。异步检索特定向量存储文件批次中的文件列表
type: docs
weight: 330
url: /zh/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchfilesasync/
---
## IOpenAIClient.GetVectorStoreFileBatchFilesAsync 方法

异步检索特定向量存储文件批次中的文件列表。

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFileBatchFilesAsync(string vectorStoreId, 
    string fileBatchId, VectorStoreFileBatchFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vectorStoreId | 字符串 | 包含文件批次的向量存储的 ID。 |
| fileBatchId | 字符串 | 要从中检索文件的文件批次的 ID。 |
| queryParameters | VectorStoreFileBatchFileListQueryParameters | 可选查询参数，用于过滤文件列表。 |
| cancellationToken | 可空`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含文件批次中的文件列表。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当向量存储 ID 为 null 或空时抛出。 |
| [AIClientException](../../aiclientexception/) | 当向量存储文件批次 ID 为 null 或空时抛出。 |

### 另请参阅

* 类 [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* 类 [VectorStoreFileBatchFileListQueryParameters](../../vectorstorefilebatchfilelistqueryparameters/)
* 接口 [IOpenAIClient](../)
* 命名空间 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../../)