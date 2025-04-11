---
title: OpenAIClient.CreateVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient 方法。异步创建新的向量存储
type: docs
weight: 100
url: /zh/net/aspose.pdf.ai/openaiclient/createvectorstoreasync/
---
## OpenAIClient.CreateVectorStoreAsync 方法

异步创建新的向量存储。

```csharp
public Task<VectorStoreResponse> CreateVectorStoreAsync(
    VectorStoreCreateRequest vectorStoreCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vectorStoreCreateRequest | VectorStoreCreateRequest | 包含创建向量存储详细信息的请求对象。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含来自向量存储创建的响应。

### 另请参阅

* 类 [VectorStoreResponse](../../vectorstoreresponse/)
* 类 [VectorStoreCreateRequest](../../vectorstorecreaterequest/)
* 类 [OpenAIClient](../)
* 命名空间 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../../)