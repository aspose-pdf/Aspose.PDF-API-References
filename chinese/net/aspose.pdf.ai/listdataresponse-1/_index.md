---
title: Class ListDataResponseT
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ListDataResponse1T 类。表示一个包含附加信息的列表数据响应，例如第一个和最后一个 ID 以及是否还有更多项目
type: docs
weight: 670
url: /zh/net/aspose.pdf.ai/listdataresponse-1/
---
## ListDataResponse&lt;T&gt; 类

表示一个包含附加信息的列表数据响应，例如第一个和最后一个 ID 以及是否还有更多项目。

```csharp
public class ListDataResponse<T> : DataResponse<T>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ListDataResponse](listdataresponse/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Data](../../aspose.pdf.ai/dataresponse-1/data/) { get; set; } |  |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | 获取或设置响应详细信息。 |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | 获取或设置 HTTP 响应错误。 |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | 获取或设置错误信息。 |
| [FirstId](../../aspose.pdf.ai/listdataresponse-1/firstid/) { get; set; } | 获取或设置列表中的第一个 ID。 |
| [HasMore](../../aspose.pdf.ai/listdataresponse-1/hasmore/) { get; set; } | 获取或设置一个值，指示列表中是否还有更多项目。 |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | 获取或设置 HTTP 响应头。 |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | 获取或设置 HTTP 状态代码。 |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 指示响应是否成功。 |
| [LastId](../../aspose.pdf.ai/listdataresponse-1/lastid/) { get; set; } | 获取或设置列表中的最后一个 ID。 |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | 获取错误原因短语。 |

### 另请参阅

* 类 [DataResponse&lt;T&gt;](../dataresponse-1/)
* 命名空间 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../)