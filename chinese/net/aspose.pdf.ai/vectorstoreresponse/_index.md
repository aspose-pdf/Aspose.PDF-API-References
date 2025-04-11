---
title: Class VectorStoreResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.VectorStoreResponse class. 向量存储对象
type: docs
weight: 1390
url: /zh/net/aspose.pdf.ai/vectorstoreresponse/
---
## VectorStoreResponse class

向量存储对象。

```csharp
public class VectorStoreResponse : BaseResponse, IEntityId, IStatus
```

## Constructors

| Name | Description |
| --- | --- |
| [VectorStoreResponse](vectorstoreresponse/)() | 默认构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/vectorstoreresponse/createdat/) { get; set; } | 获取或设置向量存储创建时的 Unix 时间戳（以秒为单位）。 |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | 获取或设置响应详细信息。 |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | 获取或设置 HTTP 响应错误。 |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | 获取或设置错误信息。 |
| [ExpiresAfter](../../aspose.pdf.ai/vectorstoreresponse/expiresafter/) { get; set; } | 获取或设置向量存储的过期策略。 |
| [ExpiresAt](../../aspose.pdf.ai/vectorstoreresponse/expiresat/) { get; set; } | 获取或设置向量存储过期时的 Unix 时间戳（以秒为单位）。 |
| [FileCounts](../../aspose.pdf.ai/vectorstoreresponse/filecounts/) { get; set; } | 获取或设置已处理文件的数量。 |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | 获取或设置 HTTP 响应头。 |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | 获取或设置 HTTP 状态代码。 |
| [Id](../../aspose.pdf.ai/vectorstoreresponse/id/) { get; set; } | 获取或设置标识符，可以在 API 端点中引用。 |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 指示响应是否成功。 |
| [LastActiveAt](../../aspose.pdf.ai/vectorstoreresponse/lastactiveat/) { get; set; } | 获取或设置向量存储最后活动时的 Unix 时间戳（以秒为单位）。 |
| [Metadata](../../aspose.pdf.ai/vectorstoreresponse/metadata/) { get; set; } | 获取或设置一组 16 个键值对，可以附加到对象上。这对于以结构化格式存储有关对象的附加信息非常有用。键的最大长度为 64 个字符，值的最大长度为 512 个字符。 |
| [Name](../../aspose.pdf.ai/vectorstoreresponse/name/) { get; set; } | 获取或设置向量存储的名称。 |
| [Object](../../aspose.pdf.ai/vectorstoreresponse/object/) { get; set; } | 获取或设置对象类型，始终为 vector_store。 |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | 获取错误原因短语。 |
| [Status](../../aspose.pdf.ai/vectorstoreresponse/status/) { get; set; } | 获取或设置向量存储的状态，可以是 expired、in_progress 或 completed。状态为 completed 表示向量存储已准备好使用。 |
| [UsageBytes](../../aspose.pdf.ai/vectorstoreresponse/usagebytes/) { get; set; } | 获取或设置向量存储中文件使用的总字节数。 |

### See Also

* class [BaseResponse](../baseresponse/)
* interface [IEntityId](../ientityid/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)