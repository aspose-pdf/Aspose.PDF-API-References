---
title: "IOpenAIClient.DeleteFileAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "IOpenAIClient 方法。异步删除特定文件。"
type: docs
weight: 140
url: /zh/net/aspose.pdf.ai/iopenaiclient/deletefileasync/
---
## IOpenAIClient.DeleteFileAsync method

异步删除特定文件。

```csharp
public Task<DeleteStatusResponse> DeleteFileAsync(string fileId, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileId | String | 要删除的文件 ID。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含删除操作的状态。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当文件 Id 为 null 或为空时抛出。 |

### 另请参见

* class [DeleteStatusResponse](../../deletestatusresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


