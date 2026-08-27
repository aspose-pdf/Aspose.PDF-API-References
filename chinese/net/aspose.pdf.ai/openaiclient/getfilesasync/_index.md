---
title: "OpenAIClient.GetFilesAsync"
second_title: "Aspose.PDF for .NET API 参考"
description: "OpenAIClient 方法。根据指定的目的异步检索文件列表。"
type: docs
weight: 230
url: /zh/net/aspose.pdf.ai/openaiclient/getfilesasync/
---
## OpenAIClient.GetFilesAsync method

根据指定目的，异步检索文件列表。

```csharp
public Task<FileListResponse> GetFilesAsync(string purpose = null, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| purpose | String | 可选。要检索的文件的目的。如果为 null，则检索所有目的的文件。 |
| cancellationToken | Nullable`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含文件列表。

### 另请参见

* class [FileListResponse](../../filelistresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


