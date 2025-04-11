---
title: CreateEmbeddingRequest.Input
second_title: Aspose.PDF for .NET API Reference
description: CreateEmbeddingRequest 属性。获取或设置要嵌入的输入文本，编码为字符串或令牌数组。要在单个请求中嵌入多个输入，请传递字符串数组或令牌数组。输入不得超过模型的最大输入令牌（textembeddingada002 的最大为 8192 个令牌），不能是空字符串，任何数组的维度必须小于或等于 2048。
type: docs
weight: 40
url: /zh/net/aspose.pdf.ai/createembeddingrequest/input/
---
## CreateEmbeddingRequest.Input 属性

获取或设置要嵌入的输入文本，编码为字符串或令牌数组。要在单个请求中嵌入多个输入，请传递字符串数组或令牌数组。输入不得超过模型的最大输入令牌（8192 个令牌用于 text-embedding-ada-002），不能是空字符串，任何数组的维度必须小于或等于 2048。

```csharp
public string Input { get; set; }
```

### 另请参阅

* 类 [CreateEmbeddingRequest](../)
* 命名空间 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 程序集 [Aspose.PDF](../../../)