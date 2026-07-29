---
title: "IOpenAIClient.CreateVectorStoreFileAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "IOpenAIClient 方法。异步创建新的向量存储文件"
type: docs
weight: 110
url: /zh/net/aspose.pdf.ai/iopenaiclient/createvectorstorefileasync/
---
## IOpenAIClient.CreateVectorStoreFileAsync method

异步创建新的向量存储文件。

```csharp
public Task<VectorStoreFileResponse> CreateVectorStoreFileAsync(string vectorStoreId, 
    VectorStoreFileCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vectorStoreId | String | 文件将被创建的向量存储的 ID。 |
| vectorStoreFileCreateRequest | VectorStoreFileCreateRequest | 包含创建文件详细信息的请求对象。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含文件创建的响应。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当向量存储 Id 为 null 或为空时抛出。 |

### 另请参见

* class [VectorStoreFileResponse](../../vectorstorefileresponse/)
* class [VectorStoreFileCreateRequest](../../vectorstorefilecreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


