---
title: "类 FileResponse"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.AI.FileResponse 类。FileResponse 对象表示已上传到 OpenAI 的文档"
type: docs
weight: 420
url: /zh/net/aspose.pdf.ai/fileresponse/
---
## FileResponse class

FileResponse 对象表示已上传到 OpenAI 的文档。

```csharp
public class FileResponse : BaseResponse, IEntityId
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [FileResponse](fileresponse/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Bytes](../../aspose.pdf.ai/fileresponse/bytes/) { get; set; } | 获取或设置文件的大小（字节）。 |
| [CreatedAt](../../aspose.pdf.ai/fileresponse/createdat/) { get; set; } | 获取或设置文件创建时的 Unix 时间戳（秒）。 |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | 获取或设置响应详情。 |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | 获取或设置 HTTP 响应错误。 |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | 获取或设置错误信息。 |
| [Filename](../../aspose.pdf.ai/fileresponse/filename/) { get; set; } | 获取或设置文件的名称。 |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | 获取或设置 HTTP 响应头。 |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | 获取或设置 HTTP 状态码。 |
| [Id](../../aspose.pdf.ai/fileresponse/id/) { get; set; } | 获取或设置文件标识符，可在 API 端点中引用。 |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 指示响应是否成功。 |
| [Object](../../aspose.pdf.ai/fileresponse/object/) { get; set; } | 获取或设置对象类型，该类型始终为 file。 |
| [Purpose](../../aspose.pdf.ai/fileresponse/purpose/) { get; set; } | 获取或设置文件的预期用途。支持的值包括 assistants、assistants_output、batch、batch_output、fine-tune、fine-tune-results 和 vision。 |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | 获取错误原因短语。 |

### 另请参见

* class [BaseResponse](../baseresponse/)
* interface [IEntityId](../ientityid/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


