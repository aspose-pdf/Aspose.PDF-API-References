---
title: SideBySidePdfComparer.Compare
second_title: Aspose.PDF for .NET API Reference
description: SideBySidePdfComparer 方法。比较两个页面。结果保存在一个 PDF 文档中，其中第一页先写入，然后是第二页。您可以在 Adobe Acrobat 中以双页视图打开它，以并排查看更改。删除在左侧页面上标记，插入在右侧页面上标记。
type: docs
weight: 10
url: /zh/net/aspose.pdf.comparison/sidebysidepdfcomparer/compare/
---
## Compare(Page, Page, string, SideBySideComparisonOptions) {#compare_1}

比较两个页面。结果保存在一个 PDF 文档中，其中第一页先写入，然后是第二页。您可以在 Adobe Acrobat 中以双页视图打开它，以并排查看更改。删除在左侧页面上标记，插入在右侧页面上标记。

```csharp
public static void Compare(Page page1, Page page2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page1 | Page | 要比较的第一页。 |
| page2 | Page | 要比较的第二页。 |
| targetPdfPath | String | 保存比较结果的 PDF 文件路径。 |
| options | SideBySideComparisonOptions | 比较选项。 |

### 另见

* class [Page](../../../aspose.pdf/page/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## Compare(Document, Document, string, SideBySideComparisonOptions) {#compare}

比较两个文档。页面逐一比较。被比较文档的页面一个接一个地复制到结果文档中。首先是第一个文档的第一页，然后是第二个文档的第一页。接下来是第一个文档的第二页，然后是第二个文档的第二页，依此类推。您可以在 Adobe Acrobat 中以双页视图打开它，以并排查看更改。删除在左侧页面上标记，插入在右侧页面上标记。

```csharp
public static void Compare(Document document1, Document document2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document1 | Document | 要比较的第一个文档。 |
| document2 | Document | 要比较的第二个文档。 |
| targetPdfPath | String | 保存比较结果的 PDF 文件路径。 |
| options | SideBySideComparisonOptions | 比较选项。 |

### 另见

* class [Document](../../../aspose.pdf/document/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)