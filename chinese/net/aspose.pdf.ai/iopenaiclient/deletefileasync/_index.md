---
title: IOpenAIClient.DeleteFileAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient 方法。异步删除特定文件
type: docs
weight: 140
url: /zh/net/aspose.pdf.ai/iopenaiclient/deletefileasync/
---
## IOpenAIClient.DeleteFileAsync 方法

异步删除特定文件。

```csharp
public Task<DeleteStatusResponse> DeleteFileAsync(string fileId, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileId | 字符串 | 要删除的文件的 ID。 |
| cancellationToken | 可空`1 | 取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含删除操作的状态。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当文件 ID 为 null 或空时抛出。 |

### 另请参阅

* 类 [DeleteStatusResponse](../../deletestatusresponse/)
* 接口 [IOpenAIClient](../)
* 命名空间 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../../)