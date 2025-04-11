---
title: Class TextPdfComparer
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.TextPdfComparer class. 表示一个用于比较两个 PDF 页面或 PDF 文档的类
type: docs
weight: 3320
url: /zh/net/aspose.pdf.comparison/textpdfcomparer/
---
## TextPdfComparer class

表示一个用于比较两个 PDF 页面或 PDF 文档的类。

```csharp
public class TextPdfComparer
```

## Constructors

| Name | Description |
| --- | --- |
| [TextPdfComparer](textpdfcomparer/)() | 默认构造函数。 |

## Methods

| Name | Description |
| --- | --- |
| static [AssemblyDestinationPageText](../../aspose.pdf.comparison/textpdfcomparer/assemblydestinationpagetext/)(List&lt;DiffOperation&gt;) | 从更改列表中恢复已更改的文本。 |
| static [AssemblySourcePageText](../../aspose.pdf.comparison/textpdfcomparer/assemblysourcepagetext/)(List&lt;DiffOperation&gt;) | 从更改列表中恢复原始文本。 |
| static [CompareDocumentsPageByPage](../../aspose.pdf.comparison/textpdfcomparer/comparedocumentspagebypage/#comparedocumentspagebypage)(Document, Document, ComparisonOptions) | 按页面逐页比较两个文档。 |
| static [CompareDocumentsPageByPage](../../aspose.pdf.comparison/textpdfcomparer/comparedocumentspagebypage/#comparedocumentspagebypage_1)(Document, Document, ComparisonOptions, string) | 按页面逐页比较两个文档。结果保存在 PDF 文件中。 |
| static [CompareFlatDocuments](../../aspose.pdf.comparison/textpdfcomparer/compareflatdocuments/#compareflatdocuments)(Document, Document, ComparisonOptions) | 按页面逐页比较两个文档。文档作为整体进行比较。在比较文本之前，文档页面的文本被合并为一个文本。 |
| static [CompareFlatDocuments](../../aspose.pdf.comparison/textpdfcomparer/compareflatdocuments/#compareflatdocuments_1)(Document, Document, ComparisonOptions, string) | 按页面逐页比较两个文档。结果保存在 PDF 文件中。文档作为整体进行比较。在比较文本之前，文档页面的文本被合并为一个文本。 |
| static [ComparePages](../../aspose.pdf.comparison/textpdfcomparer/comparepages/)(Page, Page, ComparisonOptions) | 比较文档页面。 |
| static [CreateComparisonStatistics](../../aspose.pdf.comparison/textpdfcomparer/createcomparisonstatistics/#createcomparisonstatistics_1)(List&lt;DiffOperation&gt;) | 获取比较统计信息。 |
| static [CreateComparisonStatistics](../../aspose.pdf.comparison/textpdfcomparer/createcomparisonstatistics/#createcomparisonstatistics)(List&lt;List&lt;DiffOperation&gt;&gt;) | 获取文档比较统计信息。 |

### See Also

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)