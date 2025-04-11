---
title: TextPdfComparer.CompareFlatDocuments
second_title: Aspose.PDF for .NET API Reference
description: TextPdfComparer 方法。逐页比较两个文档。文档作为一个整体进行比较。在比较文本之前，文档页面的文本被合并为一个文本
type: docs
weight: 50
url: /zh/net/aspose.pdf.comparison/textpdfcomparer/compareflatdocuments/
---
## CompareFlatDocuments(Document, Document, ComparisonOptions) {#compareflatdocuments}

逐页比较两个文档。文档作为一个整体进行比较。在比较文本之前，文档页面的文本被合并为一个文本。

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document1 | Document | 第一个文档。 |
| document2 | Document | 第二个文档。 |
| options | ComparisonOptions | 比较选项。 |

### 返回值

更改列表。

### 另见

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareFlatDocuments(Document, Document, ComparisonOptions, string) {#compareflatdocuments_1}

逐页比较两个文档。结果保存在 PDF 文件中。文档作为一个整体进行比较。在比较文本之前，文档页面的文本被合并为一个文本。

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options, string resultPdfDocumentPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document1 | Document | 第一个文档。 |
| document2 | Document | 第二个文档。 |
| options | ComparisonOptions | 比较选项。 |
| resultPdfDocumentPath | String | 保存比较结果的 PDF 文件路径。 |

### 返回值

更改列表。

### 另见

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)