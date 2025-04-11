---
title: Class CreateEmbeddingRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.CreateEmbeddingRequest 类。表示对创建嵌入端点的请求
type: docs
weight: 260
url: /zh/net/aspose.pdf.ai/createembeddingrequest/
---
## CreateEmbeddingRequest 类

表示对创建嵌入端点的请求。

```csharp
public class CreateEmbeddingRequest
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CreateEmbeddingRequest](createembeddingrequest/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Dimensions](../../aspose.pdf.ai/createembeddingrequest/dimensions/) { get; set; } | 获取或设置生成的输出嵌入应具有的维度数量。仅在 text-embedding-3 及更高版本的模型中支持。 |
| [EncodingFormat](../../aspose.pdf.ai/createembeddingrequest/encodingformat/) { get; set; } | 获取或设置返回嵌入的格式。可以是 float 或 base64。 |
| [Input](../../aspose.pdf.ai/createembeddingrequest/input/) { get; set; } | 获取或设置要嵌入的输入文本，编码为字符串或令牌数组。要在单个请求中嵌入多个输入，请传递字符串数组或令牌数组的数组。输入不得超过模型的最大输入令牌（text-embedding-ada-002 的最大为 8192 个令牌），不能是空字符串，任何数组的维度不得超过 2048。 |
| [Model](../../aspose.pdf.ai/createembeddingrequest/model/) { get; set; } | 获取或设置用于生成嵌入的模型。 |
| [User](../../aspose.pdf.ai/createembeddingrequest/user/) { get; set; } | 获取或设置一个唯一标识符，代表您的最终用户，这可以帮助 OpenAI 监控和检测滥用。 |

### 另请参见

* 命名空间 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../)