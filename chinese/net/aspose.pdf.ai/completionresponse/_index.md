---
title: Class CompletionResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.CompletionResponse 类。表示基于提供的输入返回的聊天完成响应
type: docs
weight: 240
url: /zh/net/aspose.pdf.ai/completionresponse/
---
## CompletionResponse class

表示基于提供的输入返回的聊天完成响应。

```csharp
public class CompletionResponse : BaseResponse
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CompletionResponse](completionresponse/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Choices](../../aspose.pdf.ai/completionresponse/choices/) { get; set; } | 获取或设置聊天完成选择的列表。如果 n 大于 1，则可以有多个。 |
| [Created](../../aspose.pdf.ai/completionresponse/created/) { get; set; } | 获取或设置聊天完成创建时的 Unix 时间戳（以秒为单位）。 |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | 获取或设置响应详细信息。 |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | 获取或设置 HTTP 响应错误。 |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | 获取或设置错误信息。 |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | 获取或设置 HTTP 响应头。 |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | 获取或设置 HTTP 状态代码。 |
| [Id](../../aspose.pdf.ai/completionresponse/id/) { get; set; } | 获取或设置聊天完成的唯一标识符。 |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | 指示响应是否成功。 |
| [Model](../../aspose.pdf.ai/completionresponse/model/) { get; set; } | 获取或设置用于聊天完成的模型。 |
| [Object](../../aspose.pdf.ai/completionresponse/object/) { get; set; } | 获取或设置对象类型，始终为 chat.completion。 |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | 获取错误原因短语。 |
| [SystemFingerprint](../../aspose.pdf.ai/completionresponse/systemfingerprint/) { get; set; } | 获取或设置表示模型运行的后端配置的指纹。可以与种子请求参数结合使用，以了解何时进行了可能影响确定性的后端更改。 |
| [Usage](../../aspose.pdf.ai/completionresponse/usage/) { get; set; } | 获取或设置完成请求的使用统计信息。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/completionresponse/tostring/)() | 返回第一个选择的内容作为字符串。 |

### 另请参阅

* 类 [BaseResponse](../baseresponse/)
* 命名空间 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../)