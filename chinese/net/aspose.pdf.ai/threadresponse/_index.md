---
title: "类 ThreadResponse"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.AI.ThreadResponse 类。表示包含消息的线程。"
type: docs
weight: 1270
url: /zh/net/aspose.pdf.ai/threadresponse/
---
## ThreadResponse class

表示包含消息的线程。

```csharp
public class ThreadResponse : BaseResponse
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ThreadResponse](threadresponse/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/threadresponse/createdat/) { get; set; } | 获取或设置线程创建时的 Unix 时间戳（秒）。 |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | 获取或设置响应详情。 |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | 获取或设置 HTTP 响应错误。 |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | 获取或设置错误信息。 |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | 获取或设置 HTTP 响应头。 |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | 获取或设置 HTTP 状态码。 |
| [Id](../../aspose.pdf.ai/threadresponse/id/) { get; set; } | 获取或设置标识符，可在 API 端点中引用。 |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 指示响应是否成功。 |
| [Metadata](../../aspose.pdf.ai/threadresponse/metadata/) { get; set; } | 获取或设置可附加到对象的 16 对键值对。这对于以结构化格式存储对象的附加信息很有用。键的最大长度为 64 个字符，值的最大长度为 512 个字符。 |
| [Object](../../aspose.pdf.ai/threadresponse/object/) { get; set; } | 获取或设置对象类型，该类型始终为 thread。 |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | 获取错误原因短语。 |
| [ToolResources](../../aspose.pdf.ai/threadresponse/toolresources/) { get; set; } | 获取或设置在此线程中提供给助手工具的一组资源。这些资源针对工具类型而定。例如，code_interpreter 工具需要文件 ID 列表，而 file_search 工具需要向量存储 ID 列表。 |

### 另请参见

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


