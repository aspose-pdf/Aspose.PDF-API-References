---
title: "类 CreateEmbeddingRequest"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.AI.CreateEmbeddingRequest 类。表示对 Create Embeddings 端点的请求"
type: docs
weight: 270
url: /zh/net/aspose.pdf.ai/createembeddingrequest/
---
## CreateEmbeddingRequest class

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
| [Dimensions](../../aspose.pdf.ai/createembeddingrequest/dimensions/) { get; set; } | 获取或设置生成的输出嵌入应具有的维度数量。仅在 text-embedding-3 及更高模型中受支持。 |
| [EncodingFormat](../../aspose.pdf.ai/createembeddingrequest/encodingformat/) { get; set; } | 获取或设置返回嵌入的格式。可以是 float 或 base64。 |
| [Input](../../aspose.pdf.ai/createembeddingrequest/input/) { get; set; } | 获取或设置要嵌入的输入文本，编码为字符串或标记数组。要在单个请求中嵌入多个输入，请传递字符串数组或标记数组的数组。输入不得超过模型的最大输入标记数（text-embedding-ada-002 为 8192 标记），不能为空字符串，且任何数组的维度必须不超过 2048。 |
| [Model](../../aspose.pdf.ai/createembeddingrequest/model/) { get; set; } | 获取或设置用于生成嵌入的模型。 |
| [User](../../aspose.pdf.ai/createembeddingrequest/user/) { get; set; } | 获取或设置代表终端用户的唯一标识符，可帮助 OpenAI 监控和检测滥用行为。 |

### 另请参见

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


