---
title: OpenAIClient.GetVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient 方法。异步检索特定向量存储的详细信息
type: docs
weight: 330
url: /zh/net/aspose.pdf.ai/openaiclient/getvectorstoreasync/
---
## OpenAIClient.GetVectorStoreAsync 方法

异步检索特定向量存储的详细信息。

```csharp
public Task<VectorStoreResponse> GetVectorStoreAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vectorStoreId | 字符串 | 要检索的向量存储的 ID。 |
| cancellationToken | 可空`1 | 取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含向量存储的详细信息。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当向量存储 ID 为 null 或空时抛出。 |

### 另请参阅

* 类 [VectorStoreResponse](../../vectorstoreresponse/)
* 类 [OpenAIClient](../)
* 命名空间 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../../)