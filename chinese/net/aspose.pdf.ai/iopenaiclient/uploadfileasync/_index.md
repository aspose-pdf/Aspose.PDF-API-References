---
title: IOpenAIClient.UploadFileAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient 方法。异步上传文件到 OpenAI 服务器
type: docs
weight: 420
url: /zh/net/aspose.pdf.ai/iopenaiclient/uploadfileasync/
---
## IOpenAIClient.UploadFileAsync 方法

异步上传文件到 OpenAI 服务器。

```csharp
public Task<FileResponse> UploadFileAsync(string purpose, string fileName, byte[] fileBytes, 
    CancellationToken? cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| purpose | 字符串 | 文件上传的目的，通常描述文件将如何使用。 |
| fileName | 字符串 | 要上传的文件名。 |
| fileBytes | 字节数组 | 包含文件数据的字节数组。 |
| cancellationToken | 可空`1 | 用于取消操作的令牌。 |

### 返回值

表示异步操作的任务。任务结果包含文件上传的响应。

### 异常

| 异常 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | 当文件目的为 null 或空时抛出。 |
| [AIClientException](../../aiclientexception/) | 当文件名为 null 或空时抛出。 |

### 另请参阅

* 类 [FileResponse](../../fileresponse/)
* 接口 [IOpenAIClient](../)
* 命名空间 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../../)