---
title: "OpenAIClient.GetVectorStoreAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "OpenAIClient 方法。异步检索特定向量存储的详细信息"
type: docs
weight: 340
url: /zh/net/aspose.pdf.ai/openaiclient/getvectorstoreasync/
---
## OpenAIClient.GetVectorStoreAsync method

异步检索特定向量存储的详细信息。

```csharp
public Task<VectorStoreResponse> GetVectorStoreAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vectorStoreId | String | 要检索的向量存储 ID。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含向量存储的详细信息。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当向量存储 Id 为 null 或为空时抛出。 |

### 另请参见

* class [VectorStoreResponse](../../vectorstoreresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


