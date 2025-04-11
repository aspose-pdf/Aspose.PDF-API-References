---
title: IOpenAIClient.CreateVectorStoreAndWaitToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient 方法。创建一个新的向量存储并等待其异步完成
type: docs
weight: 90
url: /zh/net/aspose.pdf.ai/iopenaiclient/createvectorstoreandwaittocompleteasync/
---
## IOpenAIClient.CreateVectorStoreAndWaitToCompleteAsync 方法

创建一个新的向量存储并等待其异步完成。

```csharp
public Task<VectorStoreResponse> CreateVectorStoreAndWaitToCompleteAsync(
    VectorStoreCreateRequest vectorStoreCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vectorStoreCreateRequest | VectorStoreCreateRequest | 包含创建向量存储详细信息的请求对象。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含向量存储创建完成后的响应。

### 另请参阅

* class [VectorStoreResponse](../../vectorstoreresponse/)
* class [VectorStoreCreateRequest](../../vectorstorecreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)