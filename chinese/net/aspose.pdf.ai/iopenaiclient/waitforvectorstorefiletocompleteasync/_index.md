---
title: "IOpenAIClient.WaitForVectorStoreFileToCompleteAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "IOpenAIClient 方法。异步等待特定向量存储文件完成"
type: docs
weight: 460
url: /zh/net/aspose.pdf.ai/iopenaiclient/waitforvectorstorefiletocompleteasync/
---
## IOpenAIClient.WaitForVectorStoreFileToCompleteAsync method

异步等待特定向量存储文件完成。

```csharp
public Task<VectorStoreFileResponse> WaitForVectorStoreFileToCompleteAsync(string vectorStoreId, 
    string fileId, CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vectorStoreId | String | 包含该文件的向量存储的 ID。 |
| fileId | String | 要监视直至完成的文件的 ID。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含文件的最终状态。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当向量存储 Id 为 null 或为空时抛出。 |
| [AIClientException](../../aiclientexception/) | 当文件 Id 为 null 或为空时抛出。 |

### 另请参见

* class [VectorStoreFileResponse](../../vectorstorefileresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


