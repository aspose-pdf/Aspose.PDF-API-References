---
title: "IOpenAIClient.WaitForVectorStoreToCompleteAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "IOpenAIClient 方法。等待特定向量存储异步完成"
type: docs
weight: 470
url: /zh/net/aspose.pdf.ai/iopenaiclient/waitforvectorstoretocompleteasync/
---
## IOpenAIClient.WaitForVectorStoreToCompleteAsync method

异步等待特定向量存储完成。

```csharp
public Task<VectorStoreResponse> WaitForVectorStoreToCompleteAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vectorStoreId | String | 要监视直至完成的向量存储的 ID。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含向量存储的最终状态。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当向量存储 Id 为 null 或为空时抛出。 |

### 另请参见

* class [VectorStoreResponse](../../vectorstoreresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


