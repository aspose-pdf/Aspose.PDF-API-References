---
title: DocSaveOptions.RelativeHorizontalProximity
second_title: Aspose.PDF for .NET API Reference
description: DocSaveOptions 属性。在 PDF 中，单词可能通过独立打印其字母或音节的操作符内部表示。因此，为了检测单词，有时我们需要检测实际上是单词的独立字符组。此设置定义了文本元素（字母、音节）之间的空白宽度，在识别源 PDF 中的单词时，必须将其视为单词之间的距离。（字母之间至少有此宽度的空白意味着文本元素属于不同的单词）。它的标准化字体大小 - 1.0 意味着假定单词字体大小的 100%。注意！仅在源 PDF 包含特定的、很少使用的字体时使用此设置，此时无法从字体计算出最佳值。因此，在绝大多数情况下，此参数对结果文档没有任何影响。
type: docs
weight: 120
url: /zh/net/aspose.pdf/docsaveoptions/relativehorizontalproximity/
---
## DocSaveOptions.RelativeHorizontalProximity 属性

在 PDF 中，单词可能通过独立打印其字母或音节的操作符内部表示。因此，为了检测单词，有时我们需要检测实际上是单词的独立字符组。此设置定义了文本元素（字母、音节）之间的空白宽度，在识别源 PDF 中的单词时，必须将其视为单词之间的距离。（字母之间至少有此宽度的空白意味着文本元素属于不同的单词）。它的标准化字体大小 - 1.0 意味着假定单词字体大小的 100%。注意！仅在源 PDF 包含特定的、很少使用的字体时使用此设置，此时无法从字体计算出最佳值。因此，在绝大多数情况下，此参数对结果文档没有任何影响。

```csharp
public float RelativeHorizontalProximity { get; set; }
```

### 另请参阅

* 类 [DocSaveOptions](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)