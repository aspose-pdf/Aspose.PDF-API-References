---
title: "DocSaveOptions.RelativeHorizontalProximity"
second_title: "Aspose.PDF for .NET API 参考"
description: "DocSaveOptions 属性。在 Pdf 中，单词可能通过运算符内部表示，这些运算符通过独立打印字母或音节来输出单词。因此，为了检测单词，有时需要检测实际上是单词的独立字符组。此设置定义文本元素（字母、音节）之间的空间宽度，在源 PDF 的单词识别过程中应视为单词之间的距离。若字母之间的空白至少达到此宽度，则表示这些文本元素属于不同的单词。其标准化值相对于字体大小，1.0 表示相当于字体大小的 100%。注意：仅在源 PDF 包含特定罕见字体且无法从字体计算出最佳值的情况下使用。因此在绝大多数情况下，此参数对结果文档没有影响。"
type: docs
weight: 120
url: /zh/net/aspose.pdf/docsaveoptions/relativehorizontalproximity/
---
## DocSaveOptions.RelativeHorizontalProximity property

在 PDF 中，单词可能通过独立打印其字母或音节的操作符内部表示。因此，要检测单词时，有时需要识别实际上构成单词的独立字符组。此设置定义文本元素（字母、音节）之间的空白宽度，在源 PDF 的单词识别过程中将其视为单词之间的距离。（如果字母之间的空白至少达到此宽度，则表示这些文本元素属于不同的单词）。该值以字体大小为基准进行归一化——1.0 表示相当于预期单词字体大小的 100%。注意！仅在源 PDF 包含特定少用字体且无法从字体本身计算出最佳值的情况下使用。因此，在绝大多数情况下，此参数对结果文档没有任何影响。

```csharp
public float RelativeHorizontalProximity { get; set; }
```

### 另请参见

* class [DocSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


