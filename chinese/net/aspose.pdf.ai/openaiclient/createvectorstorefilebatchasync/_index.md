---
title: "OpenAIClient.CreateVectorStoreFileBatchAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "OpenAIClient 方法。异步创建新的向量存储文件批次"
type: docs
weight: 120
url: /zh/net/aspose.pdf.ai/openaiclient/createvectorstorefilebatchasync/
---
## OpenAIClient.CreateVectorStoreFileBatchAsync method

异步创建新的向量存储文件批次。

```csharp
public Task<VectorStoreFileBatchResponse> CreateVectorStoreFileBatchAsync(string vectorStoreId, 
    VectorStoreFileBatchCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vectorStoreId | String | 将创建文件批次的向量存储的 ID。 |
| vectorStoreFileCreateRequest | VectorStoreFileBatchCreateRequest | 包含创建文件批次详细信息的请求对象。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含文件批次创建的响应。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当向量存储 Id 为 null 或为空时抛出。 |

### 另请参见

* class [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* class [VectorStoreFileBatchCreateRequest](../../vectorstorefilebatchcreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


