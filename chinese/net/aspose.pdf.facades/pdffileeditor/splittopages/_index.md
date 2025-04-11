---
title: PdfFileEditor.SplitToPages
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 方法。将 PDF 文件拆分为单页文档
type: docs
weight: 370
url: /zh/net/aspose.pdf.facades/pdffileeditor/splittopages/
---
## SplitToPages(string) {#splittopages_1}

将 PDF 文件拆分为单页文档。

```csharp
public MemoryStream[] SplitToPages(string inputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | 字符串 | 输入 PDF 文件名。 |

### 返回值

输出 PDF 流，每个流缓冲一个单页 PDF 文档。

### 另见

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## SplitToPages(Stream) {#splittopages}

将 Pdf 文件拆分为单页文档。

```csharp
public MemoryStream[] SplitToPages(Stream inputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | 流 | 输入 Pdf 流。 |

### 返回值

包含文档页面的内存流数组。

### 另见

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## SplitToPages(string, string) {#splittopages_3}

将 Pdf 文件拆分为单页文档并保存到指定路径。路径由字段名模板指定。

```csharp
public void SplitToPages(string inputFile, string fileNameTemplate)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | 字符串 | 输入文件名。 |
| fileNameTemplate | 字符串 | 结果文件名的模板。必须包含 %NUM%，该值将被页码替换。例如，如果指定 c:/dir/page%NUM%.pdf，结果文件将具有以下名称：c:/dir/page1.pdf, c:/dir/page2.pdf 等。 |

### 另见

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## SplitToPages(Stream, string) {#splittopages_2}

将 Pdf 文件拆分为单页文档并保存到指定路径。路径由字段名模板指定。

```csharp
public void SplitToPages(Stream inputStream, string fileNameTemplate)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | 流 | 源文档的流。 |
| fileNameTemplate | 字符串 | 结果文件名的模板。必须包含 %NUM%，该值将被页码替换。例如，如果指定 c:/dir/page%NUM%.pdf，结果文件将具有以下名称：c:/dir/page1.pdf, c:/dir/page2.pdf 等。 |

### 另见

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)