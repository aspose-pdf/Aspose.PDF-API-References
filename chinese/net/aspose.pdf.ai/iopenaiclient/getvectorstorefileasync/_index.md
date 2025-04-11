---
title: IOpenAIClient.GetVectorStoreFileAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient 方法。异步检索向量存储中特定文件的详细信息
type: docs
weight: 310
url: /zh/net/aspose.pdf.ai/iopenaiclient/getvectorstorefileasync/
---
## IOpenAIClient.GetVectorStoreFileAsync 方法

异步检索向量存储中特定文件的详细信息。

```csharp
public Task<VectorStoreFileResponse> GetVectorStoreFileAsync(string vectorStoreId, string fileId, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vectorStoreId | 字符串 | 包含文件的向量存储的 ID。 |
| fileId | 字符串 | 要检索的文件的 ID。 |
| cancellationToken | 可空`1 | 取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含文件的详细信息。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当向量存储 ID 为 null 或空时抛出。 |
| [AIClientException](../../aiclientexception/) | 当文件 ID 为 null 或空时抛出。 |

### 另请参阅

* 类 [VectorStoreFileResponse](../../vectorstorefileresponse/)
* 接口 [IOpenAIClient](../)
* 命名空间 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../../)