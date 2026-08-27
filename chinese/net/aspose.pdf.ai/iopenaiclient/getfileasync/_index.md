---
title: "IOpenAIClient.GetFileAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "IOpenAIClient 方法。异步检索特定文件的详细信息"
type: docs
weight: 210
url: /zh/net/aspose.pdf.ai/iopenaiclient/getfileasync/
---
## IOpenAIClient.GetFileAsync method

异步检索特定文件的详细信息。

```csharp
public Task<FileResponse> GetFileAsync(string fileId, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileId | String | 要检索的文件的 ID。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含文件的详细信息。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当文件 Id 为 null 或为空时抛出。 |

### 另请参见

* class [FileResponse](../../fileresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


