---
title: IOpenAIClient.CreateVectorStoreFileAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient 方法。异步创建新的向量存储文件
type: docs
weight: 110
url: /zh/net/aspose.pdf.ai/iopenaiclient/createvectorstorefileasync/
---
## IOpenAIClient.CreateVectorStoreFileAsync 方法

异步创建新的向量存储文件。

```csharp
public Task<VectorStoreFileResponse> CreateVectorStoreFileAsync(string vectorStoreId, 
    VectorStoreFileCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vectorStoreId | 字符串 | 将要创建文件的向量存储的 ID。 |
| vectorStoreFileCreateRequest | VectorStoreFileCreateRequest | 包含创建文件详细信息的请求对象。 |
| cancellationToken | 可空`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含文件创建的响应。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当向量存储 ID 为 null 或空时抛出。 |

### 另请参阅

* 类 [VectorStoreFileResponse](../../vectorstorefileresponse/)
* 类 [VectorStoreFileCreateRequest](../../vectorstorefilecreaterequest/)
* 接口 [IOpenAIClient](../)
* 命名空间 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../../)