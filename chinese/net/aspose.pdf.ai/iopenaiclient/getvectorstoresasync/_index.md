---
title: IOpenAIClient.GetVectorStoresAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient 方法。异步检索向量存储列表
type: docs
weight: 350
url: /zh/net/aspose.pdf.ai/iopenaiclient/getvectorstoresasync/
---
## IOpenAIClient.GetVectorStoresAsync 方法

异步检索向量存储列表。

```csharp
public Task<VectorStoreListResponse> GetVectorStoresAsync(
    VectorStoreListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| queryParameters | VectorStoreListQueryParameters | 可选查询参数，用于过滤向量存储列表。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含向量存储列表。

### 另请参阅

* 类 [VectorStoreListResponse](../../vectorstorelistresponse/)
* 类 [VectorStoreListQueryParameters](../../vectorstorelistqueryparameters/)
* 接口 [IOpenAIClient](../)
* 命名空间 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../../)