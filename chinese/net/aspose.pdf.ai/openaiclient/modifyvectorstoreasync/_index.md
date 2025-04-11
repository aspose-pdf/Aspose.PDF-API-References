---
title: OpenAIClient.ModifyVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient 方法。异步修改现有的向量存储
type: docs
weight: 430
url: /zh/net/aspose.pdf.ai/openaiclient/modifyvectorstoreasync/
---
## OpenAIClient.ModifyVectorStoreAsync 方法

异步修改现有的向量存储。

```csharp
public Task<VectorStoreResponse> ModifyVectorStoreAsync(string vectorStoreId, 
    VectorStoreModifyRequest vectorStoreModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vectorStoreId | 字符串 | 要修改的向量存储的 ID。 |
| vectorStoreModifyRequest | VectorStoreModifyRequest | 包含修改细节的请求对象。 |
| cancellationToken | 可空`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含来自向量存储修改的响应。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当向量存储 ID 为 null 或空时抛出。 |

### 另请参阅

* 类 [VectorStoreResponse](../../vectorstoreresponse/)
* 类 [VectorStoreModifyRequest](../../vectorstoremodifyrequest/)
* 类 [OpenAIClient](../)
* 命名空间 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../../)