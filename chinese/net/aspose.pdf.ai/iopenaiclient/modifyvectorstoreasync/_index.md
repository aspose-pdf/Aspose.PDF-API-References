---
title: "IOpenAIClient.ModifyVectorStoreAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "IOpenAIClient 方法。异步修改现有向量存储。"
type: docs
weight: 400
url: /zh/net/aspose.pdf.ai/iopenaiclient/modifyvectorstoreasync/
---
## IOpenAIClient.ModifyVectorStoreAsync method

异步修改现有向量存储。

```csharp
public Task<VectorStoreResponse> ModifyVectorStoreAsync(string vectorStoreId, 
    VectorStoreModifyRequest vectorStoreModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vectorStoreId | String | 要修改的向量存储的 ID。 |
| vectorStoreModifyRequest | VectorStoreModifyRequest | 包含修改细节的请求对象。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含向量存储修改的响应。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当向量存储 Id 为 null 或为空时抛出。 |

### 另请参见

* class [VectorStoreResponse](../../vectorstoreresponse/)
* class [VectorStoreModifyRequest](../../vectorstoremodifyrequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


