---
title: TextPdfComparer.CompareDocumentsPageByPage
second_title: Aspose.PDF for .NET API Reference
description: TextPdfComparer 方法。逐页比较两个文档
type: docs
weight: 40
url: /zh/net/aspose.pdf.comparison/textpdfcomparer/comparedocumentspagebypage/
---
## CompareDocumentsPageByPage(Document, Document, ComparisonOptions) {#comparedocumentspagebypage}

逐页比较两个文档。

```csharp
public static List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, 
    Document document2, ComparisonOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document1 | Document | 第一个文档.. |
| document2 | Document | 第二个文档. |
| options | ComparisonOptions | 比较选项. |

### 返回值

按页列出更改.

### 另请参见

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareDocumentsPageByPage(Document, Document, ComparisonOptions, string) {#comparedocumentspagebypage_1}

逐页比较两个文档。结果保存在 PDF 文件中。

```csharp
public static List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, 
    Document document2, ComparisonOptions options, string resultPdfDocumentPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document1 | Document | 第一个文档.. |
| document2 | Document | 第二个文档. |
| options | ComparisonOptions | 比较选项. |
| resultPdfDocumentPath | String | 保存比较结果的 PDF 文件路径. |

### 返回值

按页列出更改.

### 另请参见

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)