---
title: "IOpenAIClient.CancelVectorStoreFileBatchAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "IOpenAIClient 方法。异步取消特定向量存储文件批次"
type: docs
weight: 20
url: /zh/net/aspose.pdf.ai/iopenaiclient/cancelvectorstorefilebatchasync/
---
## IOpenAIClient.CancelVectorStoreFileBatchAsync method

异步取消特定的向量存储文件批次。

```csharp
public Task<VectorStoreFileBatchResponse> CancelVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vectorStoreId | String | 包含要取消的文件批次的向量存储的 ID。 |
| fileBatchId | String | 要取消的文件批次的 ID。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含取消文件批次的响应。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当向量存储 Id 为 null 或为空时抛出。 |
| [AIClientException](../../aiclientexception/) | 当向量存储文件批次 Id 为 null 或为空时抛出。 |

### 另请参见

* class [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


