---
title: Class VectorStoreFileResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.VectorStoreFileResponse 类。一个向量存储文件响应
type: docs
weight: 1350
url: /zh/net/aspose.pdf.ai/vectorstorefileresponse/
---
## VectorStoreFileResponse 类

一个向量存储文件响应。

```csharp
public class VectorStoreFileResponse : BaseResponse, IStatus
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [VectorStoreFileResponse](vectorstorefileresponse/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/vectorstorefileresponse/createdat/) { get; set; } | 获取或设置向量存储文件创建时的 Unix 时间戳（以秒为单位）。 |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | 获取或设置响应详细信息。 |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | 获取或设置 HTTP 响应错误。 |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | 获取或设置错误信息。 |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | 获取或设置 HTTP 响应头。 |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | 获取或设置 HTTP 状态码。 |
| [Id](../../aspose.pdf.ai/vectorstorefileresponse/id/) { get; set; } | 获取或设置标识符，可以在 API 端点中引用。 /// |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 指示响应是否成功。 |
| [LastError](../../aspose.pdf.ai/vectorstorefileresponse/lasterror/) { get; set; } | 获取或设置与此向量存储文件相关的最后一个错误。如果没有错误，则为 null。 |
| [Object](../../aspose.pdf.ai/vectorstorefileresponse/object/) { get; set; } | 获取或设置对象类型，始终为 vector_store.file。 |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | 获取错误原因短语。 |
| [Status](../../aspose.pdf.ai/vectorstorefileresponse/status/) { get; set; } | 获取或设置向量存储文件的状态，可以是 in_progress、completed、cancelled 或 failed。状态 completed 表示向量存储文件已准备好使用。 |
| [UsageBytes](../../aspose.pdf.ai/vectorstorefileresponse/usagebytes/) { get; set; } | 获取或设置以字节为单位的总向量存储使用量。请注意，这可能与原始文件大小不同。 |
| [VectorStoreId](../../aspose.pdf.ai/vectorstorefileresponse/vectorstoreid/) { get; set; } | 获取或设置文件所附加的向量存储的 ID。 |

### 另见

* 类 [BaseResponse](../baseresponse/)
* 接口 [IStatus](../istatus/)
* 命名空间 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../)