---
title: "OpenAIClient.GetVectorStoreFileBatchAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "OpenAIClient 方法。异步检索特定向量存储文件批次的详细信息"
type: docs
weight: 360
url: /zh/net/aspose.pdf.ai/openaiclient/getvectorstorefilebatchasync/
---
## OpenAIClient.GetVectorStoreFileBatchAsync method

异步检索特定向量存储文件批次的详细信息。

```csharp
public Task<VectorStoreFileBatchResponse> GetVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vectorStoreId | String | 包含该文件批次的向量存储的 ID。 |
| fileBatchId | String | 要检索的文件批次的 ID。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含文件批次的详细信息。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当向量存储 Id 为 null 或为空时抛出。 |
| [AIClientException](../../aiclientexception/) | 当向量存储文件批次 Id 为 null 或为空时抛出。 |

### 另请参见

* class [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


